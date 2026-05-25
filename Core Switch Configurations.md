# CoreSwitch01
en
conf
hostname CoreSwitch1


vlan 200
name FW-CORE-VLAN200
vlan 300
name Internal-VLAN300
exit 

spanning-tree vlan 200,300 priority 4096
track 1 interface Port-channel1 line-protocol   

interface Port-channel1
description FW1-Uplink-Bundle
switchport trunk encapsulation dot1q
switchport mode trunk
switchport trunk allowed vlan 200
exit  

interface Port-channel2
description Peer-Link-to-CoreSwitch2
switchport trunk encapsulation dot1q
switchport mode trunk
switchport trunk allowed vlan 200,300
exit  

interface GigabitEthernet0/0
description FW1-uplink-E2
switchport trunk encapsulation dot1q
switchport mode trunk
switchport trunk allowed vlan 200
channel-group 1 mode active
exit 

  

interface GigabitEthernet0/1
description FW1-uplink-E1
switchport trunk encapsulation dot1q
switchport mode trunk
switchport trunk allowed vlan 200
channel-group 1 mode active
exit

interface GigabitEthernet1/0
description AccSw01-Uplink-G0/0
switchport trunk encapsulation dot1q
switchport mode trunk
switchport trunk allowed vlan 200,300
exit 

interface GigabitEthernet1/2
description CoreSwitch2-Link-G1/2
switchport trunk encapsulation dot1q
switchport mode trunk
switchport trunk allowed vlan 200,300
channel-group 2 mode active
exit  

interface GigabitEthernet1/3
description CoreSwitch2-Link-G1/3
switchport trunk encapsulation dot1q
switchport mode trunk
switchport trunk allowed vlan 200,300
channel-group 2 mode active
exit  

interface Vlan 200
description FW-CORE VLAN
ip address 10.2.1.250 255.255.255.0
standby 20 ip 10.2.1.251
standby 20 priority 100
standby 20 preempt delay minimum 60 reload 180
standby 20 authentication gob
standby 20 track 1 decrement 10
exit  

interface Vlan 300
description INTERNAL VLAN
ip address 10.3.1.252 255.255.255.0
ip helper-address 10.3.1.12
standby 30 ip 10.3.1.254
standby 30 priority 100
standby 30 preempt delay minimum 60 reload 180
standby 30 authentication gob
standby 30 track 1 decrement 10
exit

ip route 0.0.0.0 0.0.0.0 10.2.1.254
snmp-server community public RO
logging host 192.168.86.24
logging trap informational
service timestamps log datetime msec
snmp-server host 192.168.86.249 version 2c public
snmp-server enable traps
end
wr

# CoreSwitch02
