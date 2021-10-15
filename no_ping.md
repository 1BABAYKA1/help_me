SW2

%LINK-5-CHANGED: Interface Vlan20, changed state to up

%LINK-5-CHANGED: Interface FastEthernet0/22, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/22, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface Vlan20, changed state to up

%LINK-5-CHANGED: Interface FastEthernet0/1, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/1, changed state to up

%LINK-5-CHANGED: Interface FastEthernet0/2, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/2, changed state to up

%LINK-5-CHANGED: Interface FastEthernet0/3, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/3, changed state to up

%LINK-5-CHANGED: Interface FastEthernet0/4, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/4, changed state to up

%LINK-5-CHANGED: Interface FastEthernet0/5, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/5, changed state to up
![image](https://github.com/1BABAYKA1/systemka/blob/main/2021-10-15%20(3).png?raw=true)




SW1

%LINK-5-CHANGED: Interface Vlan10, changed state to up

%LINK-5-CHANGED: Interface Vlan20, changed state to up

%LINK-5-CHANGED: Interface Vlan30, changed state to up

%LINK-5-CHANGED: Interface FastEthernet0/22, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/22, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface Vlan20, changed state to up

%LINK-5-CHANGED: Interface FastEthernet0/23, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/23, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface Vlan30, changed state to up

%LINK-5-CHANGED: Interface FastEthernet0/1, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/1, changed state to up

%LINK-5-CHANGED: Interface FastEthernet0/2, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/2, changed state to up

%LINK-5-CHANGED: Interface FastEthernet0/3, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/3, changed state to up

%LINK-5-CHANGED: Interface FastEthernet0/4, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/4, changed state to up

%LINK-5-CHANGED: Interface FastEthernet0/5, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/5, changed state to up

%LINK-5-CHANGED: Interface GigabitEthernet0/2, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/2, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface Vlan10, changed state to up
![image](https://raw.githubusercontent.com/1BABAYKA1/systemka/main/2021-10-15%20(2).png)

Router



%LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/2, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/2.10, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/2.20, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/2.30, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface GigabitEthernet0/0, changed state to up
![image](https://github.com/1BABAYKA1/systemka/blob/main/2021-10-15%20(1).png?raw=true)


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Current configuration : 1213 bytes
!
version 15.0
no service timestamps log datetime msec
no service timestamps debug datetime msec
no service password-encryption
!
hostname SW2
!
!
!
!
!
!
spanning-tree mode pvst
spanning-tree extend system-id
!
interface FastEthernet0/1
!
interface FastEthernet0/2
interface FastEthernet0/3
!
interface FastEthernet0/4
!
interface FastEthernet0/5
!
interface FastEthernet0/6
!
interface FastEthernet0/7
!
interface FastEthernet0/8
!
interface FastEthernet0/9
!
interface FastEthernet0/10
!
interface FastEthernet0/11
!
interface FastEthernet0/12
!
interface FastEthernet0/13
!
interface FastEthernet0/14
!
interface FastEthernet0/15
!
interface FastEthernet0/16
!
interface FastEthernet0/17
!
interface FastEthernet0/18
!
interface FastEthernet0/19
!
interface FastEthernet0/20
!
interface FastEthernet0/21
!
interface FastEthernet0/22
 switchport access vlan 20
 switchport mode access
!
interface FastEthernet0/23
!
interface FastEthernet0/24
!
interface GigabitEthernet0/1
!
interface GigabitEthernet0/2
 switchport access vlan 20
 switchport mode access
!
interface Vlan1
 no ip address
 shutdown
!
interface Vlan20
 no ip address
!
!
!
!
line con 0
!
line vty 0 4
 login
line vty 5 15
 login
 --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 Current configuration : 1332 bytes
!
version 15.0
no service timestamps log datetime msec
no service timestamps debug datetime msec
no service password-encryption
!
hostname SW1
!
!
!
!
!
!
spanning-tree mode pvst
spanning-tree extend system-id
!
interface FastEthernet0/1
!
interface FastEthernet0/2
!
interface FastEthernet0/3
!
interface FastEthernet0/4
!
interface FastEthernet0/5
!
interface FastEthernet0/6
!
interface FastEthernet0/7
!
interface FastEthernet0/8
!
interface FastEthernet0/9
!
interface FastEthernet0/10
!
interface FastEthernet0/11
!
interface FastEthernet0/12
!
interface FastEthernet0/13
!
interface FastEthernet0/14
!
interface FastEthernet0/15
!
interface FastEthernet0/16
!
interface FastEthernet0/17
!
interface FastEthernet0/18
!
interface FastEthernet0/19
!
interface FastEthernet0/20
!
interface FastEthernet0/21
!
interface FastEthernet0/22
 switchport access vlan 20
 switchport mode access
!
interface FastEthernet0/23
 switchport access vlan 30
 switchport mode access
!
interface FastEthernet0/24
!
interface GigabitEthernet0/1
!
interface GigabitEthernet0/2
 switchport access vlan 10
 switchport mode access
!
interface Vlan1
 no ip address
 shutdown
!
interface Vlan10
 no ip address
!
interface Vlan20
 no ip address
!
interface Vlan30
 no ip address
!
!
!
!
line con 0
!
line vty 0 4
 login
line vty 5 15
 login
 --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Current configuration : 1349 bytes
!
version 15.1
no service timestamps log datetime msec
no service timestamps debug datetime msec
no service password-encryption
!
hostname R1
!
!
!
!
!
ip dhcp pool Derartment2
 network 10.10.2.0 255.255.255.0
 default-router 10.10.2.254
 dns-server 8.8.8.8
ip dhcp pool Derartment1
 network 10.10.1.0 255.255.255.0
 default-router 10.10.1.254
  dns-server 8.8.8.8
!
!
!
ip cef
no ipv6 cef
!
!
!
!
license udi pid CISCO2911/K9 sn FTX1524IC4T-
!
!
!
!
!
!
!
!
!
ip name-server 8.8.8.8
!
!
spanning-tree mode pvst
!
!
!
!
!
!
interface GigabitEthernet0/0
 ip address 8.8.8.1 255.255.255.0
 ip nat inside
 duplex auto
 speed auto
!
interface GigabitEthernet0/1
 no ip address
 duplex auto
 speed auto
 shutdown
!
interface GigabitEthernet0/2
 no ip address
 duplex auto
 speed auto
!
interface GigabitEthernet0/2.10
 encapsulation dot1Q 10
 ip address 10.10.1.254 255.255.255.0
!
interface GigabitEthernet0/2.20
 encapsulation dot1Q 20
 ip address 10.10.2.254 255.255.255.0
!
interface GigabitEthernet0/2.30
 encapsulation dot1Q 30
 ip address 10.10.3.254 255.255.255.0
!
interface Vlan1
 no ip address
 shutdown
!
router rip
!
ip nat inside source list 13 interface GigabitEthernet0/2 overload
ip classless
!
ip flow-export version 9
!
!
access-list 13 permit 10.0.0.0 0.255.255.255
!
!
!
!
!
!
line con 0
!
line aux 0
!
line vty 0 4
 login 
