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

# 16.Explain LAN (Local Area Network)
LANs are widely used to connect computers/laptops and consumer electronics which enables them to share resources (e.g., printers, fax machines) and exchange information. When LANs are used by companies or organizations, they are called enterprise networks. There are two different types of LAN networks i.e. wireless LAN (no wires involved achieved using Wi-Fi) and wired LAN (achieved using LAN cable). Wireless LANs are very popular these days for places where installing wire is difficult. The below diagrams explain both wireless and wired LAN.

# 17.Describe the OSI Reference Model
Open System Interconnections (OSI) is a network architecture model based on the ISO standards. It is called the OSI model as it deals with connecting the systems that are open for communication with other systems.
The OSI model has seven layers. The principles used to arrive at the seven layers can be summarized briefly as below:
Create a new layer if a different abstraction is needed.
Each layer should have a well-defined function.
The function of each layer is chosen based on internationally standardized protocols.

# 18.What is the use of a router and how is it different from a gateway?
The router is sa networking device used for connecting two cting two or more network segments. It directs the traffic in the network. It transfers information and data like web pages, emails, images, videos, etc. from source to destination in the form of packets. It operates at the network layer. The gateways are also used to route and regulate the network traffic but, they can also send data between two dissimilar networks while a router can only send data to similar networks.

# 19.What is the TCP protocol?
TCP or TCP/IP is the Transmission Control Protocol/Internet Protocol. It is a set of rules that decides how a computer connects to the Internet and how to transmit the data over the network. It creates a virtual network when more than one computer is connected to the network and uses the three ways handshake model to establish the connection which makes it more reliable.

# 20.What is the firewall?
The firewall is a network security system that is used to monitor the incoming and outgoing traffic and blocks the same based on the firewall security policies. It acts as a wall between the internet (public network) and the networking devices (a private network). It is either a hardware device, software program, or a combination of both. It adds a layer of security to the network.

# 21.What is an IP Address?
An IP address is a unique identifier for a device on a network, like a postal address for your home. It ensures that data sent over a network reaches the correct destination.

# 22.Network Types:
• LAN: Local Area Network (e.g., home or office).
• WAN: Wide Area Network (e.g., the internet).
• MAN: Metropolitan Area Network (city-wide networks).

# 23.What is Networking?
Networking is the process of connecting devices (computers, phones, servers) to exchange data and share resources. Think of it as building a digital highway for communication.

# 24.What is the difference between IPv4 and IPv6?
Explanation: IPv4 has 32-bit addresses, which provides about 4.3 billion unique addresses. IPv6, on the other hand, has 128-bit addresses, providing an almost infinite number of addresses (340 undecillion). IPv6 is designed to address the exhaustion of IPv4 addresses.
Real-time Scenario: As the number of devices connected to the internet increases (think IoT devices, smartphones), IPv4 addresses are being exhausted. This is where IPv6 comes in, allowing devices like smart refrigerators, wearables, and sensors to get unique IP addresses.

# 25.What is DNS, and how does it work?
Explanation: DNS (Domain Name System) converts human-readable domain names (like www.google.com) into IP addresses. It works like a phonebook for the internet.
Real-time Scenario: When you type a website name into your browser, your device contacts a DNS server to resolve the domain into an IP address, and then it connects to the website. Without DNS, you'd need to remember the IP addresses of every website.

# 26.How do you secure a wireless network?
Explanation: Securing a wireless network involves using strong encryption (WPA3), disabling SSID broadcasting, using strong passwords, setting up a firewall, and applying access control lists (ACLs).
Real-time Scenario: In a café, to protect against unauthorized access, the Wi-Fi network is secured with WPA3 encryption and a strong password, preventing hackers from easily connecting to the network and accessing sensitive customer data.

# 27.What is switching?
A switch is a device which is used to connect multiple devices inside Local Area Network (LAN). Unlike hubs, a switch examines each packet and process it accordingly rather than simply repeating the signal to all port. Switches operate at Layer Two (Data Link layer) of the OSI model.

# 28.What is DHCP?
Dynamic Host Configuration Protocol (DHCP) assigns IP address to hosts dynamically. It allows easier administration and works well in small as well as very large network environments. All types of hardware can be used as a DHCP server including a Cisco router.

# 29.How does switch learn Mac address?
A switch can learn MAC address in two ways; statically or dynamically. In the static option, we must add the MAC addresses in the CAM table manually. In the dynamic option, the switch learns and adds the MAC addresses in the CAM table automatically. The switch stores the CAM table in the RAM.

# 30.How does switch learn Mac address?
A switch can learn MAC address in two ways; statically or dynamically. In the static option, we must add the MAC addresses in the CAM table manually. In the dynamic option, the switch learns and adds the MAC addresses in the CAM table automatically. The switch stores the CAM table in the RAM.

