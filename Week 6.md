# Week 6

## Address Resolution Protocol (ARP)
-  Refers to the communication protocol used for discovering the link layer address, such as a MAC address, associated with a given internet layer address, typically an IPv4 address. AKA: it connects an ever-changing Internet Protocol (IP) address to a fixed physical machine address, aka the media access control (MAC) address, in a local-area network (LAN).
-  Link layer: refers to the lowest layer in the Internet protocol suite, the networking architecture of the Internet. It is responsible for transporting information from one host (or router) to another over a _single_ link. Layer 2 and 1.
-  The MAC address is also known as the data link layer, which establishes and terminates a connection between two physically connected devices so that data transfer can take place. The IP address is also referred to as the network layer or the layer responsible for forwarding packets of data through different routers. ARP works between these layers.

## Dynamic Host Configuration Protocol (DHCP)
- Refers to the network management protocol used to automate the process of configuring devices on IP networks. It allows devices to use network services such as DNS, NTP, and any communication protocol based on UDP or TCP. 
- A DHCP server dynamically assigns an IP address and other network configuration parameters, such as the subnet mask and the default gateway, to each device on a network so they can communicate with other IP networks.
### Why use DHCP?
- Every device on a TCP/IP-based network must have a unique IP address to access the network and its resources. Without DHCP, IP addresses for new computers or computers that are moved from one subnet to another must be configured manually; IP addresses for computers that are removed from the network must be manually reclaimed. With DHCP, this entire process is automated and managed centrally.