# Edge Router 1
```cisco
En
Conf t 
hostname EdgRtr1 
track 1 interface GigabitEthernet0/3 line-protocol 
interface GigabitEthernet0/0 
no ip address 
no shut 
exit

interface GigabitEthernet0/0.100 
description Link VLAN100 Interface 
encapsulation dot1Q 100 
ip address 10.1.1.252 255.255.255.0 
ip nat inside 
standby 10 ip 10.1.1.254 
standby 10 priority 105 
standby 10 preempt delay minimum 180 reload 180 
standby 10 authentication gob 
exit 

interface GigabitEthernet0/3 
description ISP Uplink 
ip address 192.168.86.103 255.255.255.0 
ip nat outside 
standby 12 ip 192.168.86.105 
standby 12 priority 105 
standby 12 preempt delay minimum 180 reload 180 
standby 12 authentication gob 
standby 12 track 1 decrement 10 
no shut 
exit 

ip route 192.168.255.0 255.255.255.0 192.168.86.29 #Tailscale access 
ip route 100.64.0.0 255.192.0.0 192.168.86.29            #Tailscale return 
ip route 0.0.0.0 0.0.0.0 192.168.86.1 
ip route 10.2.1.0 255.255.255.0 10.1.1.251 
ip route 10.3.1.0 255.255.255.0 10.1.1.251 
ip route 192.168.86.0 255.255.255.0 GigabitEthernet0/3 

no access-list 101 
access-list 101 deny ip 10.0.0.0 0.255.255.255 192.168.86.0 0.0.0.255 
access-list 101 permit ip 10.0.0.0 0.255.255.255 any 
access-list 101 permit ip 172.16.12.0 0.0.0.255 any 
ip nat inside source list 101 interface GigabitEthernet0/3 overload 
snmp-server community public RO 
snmp-server host 192.168.86.249 version 2c public 
snmp-server enable traps 
logging host 192.168.86.249 
logging trap informational 
service timestamps log datetime msec 

end 
write memory 
```
# Edge Router 2
```cisco
En
Conf t 
hostname EdgRtr2 
interface GigabitEthernet0/0 
no ip address 
no shut 
exit 

interface GigabitEthernet0/0.100 
description Link VLAN100 Interface 
encapsulation dot1Q 100 
ip address 10.1.1.253 255.255.255.0 
ip nat inside 
standby 10 ip 10.1.1.254 
standby 10 priority 100 
standby 10 authentication gob 
exit 

interface GigabitEthernet0/3 
description ISP Uplink 
ip address 192.168.86.104 255.255.255.0 
ip nat outside 
standby 12 ip 192.168.86.105 
standby 12 priority 100 
standby 12 authentication gob 
no shut 
exit 

ip route 192.168.255.0 255.255.255.0 192.168.86.29 #Tailscale access 
ip route 100.64.0.0 255.192.0.0 192.168.86.29            #Tailscale return 
ip route 0.0.0.0 0.0.0.0 192.168.86.1 
ip route 10.2.1.0 255.255.255.0 10.1.1.251 
ip route 10.3.1.0 255.255.255.0 10.1.1.251 
ip route 192.168.86.0 255.255.255.0 GigabitEthernet0/3 

no access-list 101 
access-list 101 deny ip 10.0.0.0 0.255.255.255 192.168.86.0 0.0.0.255 
access-list 101 permit ip 10.0.0.0 0.255.255.255 any 
access-list 101 permit ip 172.16.12.0 0.0.0.255 any 
ip nat inside source list 101 interface GigabitEthernet0/3 overload 
snmp-server community public RO 
snmp-server host 192.168.86.249 version 2c public 
snmp-server enable traps 
logging host 192.168.86.249 
logging trap informational 
service timestamps log datetime msec 
 
end 
write memory
```
