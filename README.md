# NetworkQ
# 1.Explain OSI Layer?
Open system interconnect (OSI) was developed by the international organization for
standardization (ISO) and introduced in 1984.
It's a consists of seven layers Application layer, Presentation layer, Session layer, Transport layer, Network layer,Data link layer, Physical layer.

# 2.What is the range of port Number?
Well known Ports-0 to 1023
Registered Ports-1024 to 49151 Open Poerts-49152 to 65535

# 3.What is the Unicast, Multicast and Broadcast?
Unicast
In computer networking, unicast is a one-to-one transmission.
Multicast
In computer networking, multicast is group communication.
Broadcast
In computer networking, one-to-many

# 4. What is the different between Half-duplex and Full duplex?
Half Duplex-Data can flow in both direction but not simultaneously. At a time, Data can flow
only in one directional Ex-HUB.
Full Duplex-Data can flow both directional simultaneously-Switch.

# 5.What is a Protocol Number and give some examples?
The protocol number is a single byte in the third word of the datagram header. The value identifies the protocol in the layer above IP to which the data should be passed.
Protocol
Protocol Number
ICMP--1 
IGMP--2
IPV4--4
TCP--6
EGP--8
IGP--9
UDP--17
IPV6--41
GRE-47
EIGRP--88
OSPF -89
BGP--179

# 6.What are the protocols that are include by each layer of the TCP/IP model?
Application layer-DNS, DHCP, FTP, TFTP, SMTP, HTTP, Telnet, SSH.
Transport layer-TCP, UDP
Internet layer-IP, ICMP, IGMP
Network access layer-Ethernet, Token Ring, FDDI, X.25, Frame Relay, ARP, RARP.

# 7.What is the ARP?
Address Resolution Protocol (ARP) is a network protocol, which is used to map a network layer protocol address (IP address) to a data link layer hardware address (MAC address). ARP basically resolves IP address to the corresponding MAC address.

# 8.What is the MAC format?
It is a 12 Digits 48 Bit(6byte) Hardware address written in Hexadecimal format.
It consists of two parts:-
The first 24 Bits OUI (Organizationally Unique Identifier) is assigned by IEEE.
The last 24 Bits is Manufacturing-assigned Code.

# 9.What is the Routing?
The function of routing is to route packet between networks that are not locally attached.

# 10.What is the Router?
It's is a device which enables communication between two or more different logical
network.
It's a network layer-3 device.

# 11.What are the different types of Memory in the router?
RAM-Running configuration file: running-config is store in RAM.
NVRAM-Start-up configuration file: start-up configuration is stored in NVRAM
Flash Memory-IOS is stored in Flash memory
ROM-Instruction for Post, Bootstrap, Mini-IOS is Stored in ROM
# 12.What are different modes in the router?
User mode:-
Only some basic monitoring and limited show commands work in this mode.
Ex-Enable, ping, traceroute, etc. Router>
Privilege mode:-
Monitoring Troubleshooting and verification commands work in this mode.
Ex-show, configure terminal, write, etc Router#
Global Configuration mode: -
Global Configuration made in this mode affects the operation of the device.
Ex-Hostname, etc. Router(config)#

# 13 What is the Routed protocol?
A routed protocol carries data from one network to another network. Routed protocol carries user traffic such as file transfer, web traffic, e-mail.
Ex-IP, IPX and apple talk.

# 14.What is the Routing Protocol?
Routing protocols learn the routes and provide the best route from one network to another network. Ex-EIGRP, OSPF, RIP.

# 15.Explain EIGRP Routing Protocol?
Enhanced Interior Gateway Routing Protocol (EIGRP Protocol) is an enhanced distance vector routing protocol which uses Diffused Update Algorithm (DUAL) to calculate the shortest path. Is also considered as a hybrid routing protocol because it has characteristic of both Distance vector & Link State Routing Protocol.
EIGRP support classless routing & VLSM, route summarization, incremental updates, load balancing and other future.

