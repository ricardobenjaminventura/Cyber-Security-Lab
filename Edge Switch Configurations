# Switch01
hostname EXTSwitch01 

vlan 100 
name EXT-VLAN-100 
exit

interface GigabitEthernet0/0 
description Link to ISPRouter01 Gi0/0 
switchport trunk encapsulation dot1q 
switchport mode trunk 
negotiation auto 
exit

interface GigabitEthernet0/1 
description Link to pfSense01 e0 
switchport trunk encapsulation dot1q 
switchport mode trunk 
negotiation auto
exit

interface GigabitEthernet0/2 
description Link to EXTSwitch02 Gi0/2 
switchport trunk encapsulation dot1q 
switchport mode trunk 
negotiation auto
exit

snmp-server community public RO 
logging host 192.168.86.249 
logging trap informational 
service timestamps log datetime msec 
snmp-server host 192.168.86.249 version 2c public 
snmp-server enable traps
end
wr

# Switch02
En
Conf t 
hostname EXTSwitch02 

vlan 100 
name EXT-VLAN-100 
Exit 

interface GigabitEthernet0/0 
description Link to ISPRouter02 Gi0/0 
switchport trunk encapsulation dot1q 
switchport mode trunk 
negotiation auto 
exit  

interface GigabitEthernet0/1 
description Link to pfSense02 e0 
switchport trunk encapsulation dot1q 
switchport mode trunk 
negotiation auto 
exit  

interface GigabitEthernet0/2 
description Link to EXTSwitch01 Gi0/2 
switchport trunk encapsulation dot1q 
switchport mode trunk 
negotiation auto 
Exit 

Int range gi0/0-2 
No shut 
snmp-server community public RO 
logging host 192.168.86.249 
logging trap informational 
service timestamps log datetime msec 
snmp-server host 192.168.86.249 version 2c public 
snmp-server enable traps 
End 
Copy running-config startup-config 
