# Week 3

## Client to Server Stack
- Refers to a web client interacting with a web server.
	- Ex. A Firefox web client requests information from an Apache web server. For instance, you may enter your user credentials to log into your twitter account.
	
## Four Layers of OSI model: 
1. Application:
	- Application:
		- Interfaces like HTTP and SQL communicate on this layer.
		- High-level protocols like DNS (Domain Naming Service), HTTP (Hypertext Transfer Protocol), Telnet, SSH (Secure Shell), FTP (File Transfer Protocol), SMTP (Simple Mail Transfer Protocol), etc.
	- Presentation:
		- Formatting. If the client and server run on different operating systems, character set differences can occur. The presentation layer resolves any differences.
		- Encryption, decryption
	- Session:
		- Conversation signaling
2. Host-to-host:
	- Transport:
		- Defines the level of service and status of the connection used when transporting data.
		- The main protocols included are TCP (Transmission Control Protocol) and UDP (User Datagram Protocol).
3. Internet:
	- Network:
		- Packs data into data packets known as IP datagrams, which contain source and destination address information that is used to forward the datagrams between hosts and across networks.
		- The Internet layer is also responsible for routing of IP datagrams, which is known as Packet Switching.
		- The main protocols included are IP (Internet Protocol), ICMP (Internet Control Message Protocol)], and ARP (Address Resolution Protocol).
4. Network Interface:
	- Data Link:
		- Defines details of how data is physically sent through the network, including how bits are electrically or optically signaled by hardware devices.
		- Protocols like FCS (Frame Check Sequence) ensure that data is not error-prone and has not been corrupted.
		- The main protocols included are Ethernet, Token Ring, FDDI, X.25, and Frame Relay.
	- Physical:
		- The interface for this process is usually a network medium like a coaxial cable, optical fiber, or twisted pair copper wire.