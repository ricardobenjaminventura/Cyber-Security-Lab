# Access Switch 1
```cisco
en
conf t
hostname AccSw01  

vlan 200
name FW-CORE-VLAN200
vlan 300
name Internal-VLAN300
exit

interface GigabitEthernet0/0
description Uplink-to-CoreSw01
switchport trunk encapsulation dot1q
switchport mode trunk
switchport trunk allowed vlan 200,300
no shut
exit

interface GigabitEthernet0/1
description LAB-Domain-Controller
switchport mode access
switchport access vlan 300
spanning-tree portfast
no shut
exit

interface GigabitEthernet0/2
description LAB-WAZUH 
switchport mode access
switchport access vlan 300
spanning-tree portfast
no shut
exit

interface Vlan 300
description Management-IP
ip address 10.3.1.250 255.255.255.0
no shut
exit

ip route 0.0.0.0 0.0.0.0 10.3.1.254

snmp-server community public RO
logging host 192.168.86.249
logging trap informational
service timestamps log datetime msec
snmp-server host 192.168.86.249 version 2c public
snmp-server enable traps

end
write memory
```
# Accesss Switch 2
```cisco
en
conf t
hostname AccSw02

vlan 200
name FW-CORE-VLAN200
vlan 300
name Internal-VLAN300
exit

interface GigabitEthernet0/0
description Uplink-to-CoreSw02
switchport trunk encapsulation dot1q
switchport mode trunk
switchport trunk allowed vlan 200,300
no shut
exit

interface GigabitEthernet0/1
description LAB-Kali
switchport mode access
switchport access vlan 300
spanning-tree portfast
no shut
exit

interface GigabitEthernet0/2
description LAB-ZABBIX
switchport mode access
switchport access vlan 300
spanning-tree portfast
no shut
exit

interface Vlan 300
description Management-IP
ip address 10.3.1.253 255.255.255.0
no shut
exit

ip route 0.0.0.0 0.0.0.0 10.3.1.254

snmp-server community public RO
logging host 192.168.86.249
logging trap informational
service timestamps log datetime msec
snmp-server host 192.168.86.249 version 2c public
snmp-server enable traps

end
write memory
```

 

 
