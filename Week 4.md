# Week 4

## Multiplexing
### Time Division
- Refers to a technique that permits the flow of multiple data signal over a communication link in different time domains.
	- Ex. Long distance routes for most modern telecommunications systems.
- Typically, it is used when the bit rate of the media is greater than that of the signal to be transmitted. Each signal is allotted a specific amount of time. These time slots are so small that all transmissions appear to be parallel. So, all signals operate within the same frequency but at different times.
### Frequency Division
- Refers to a technique that allows transmission of multiple signals using different frequency slots over a common link.
	- Ex. Radio and TV transmission
- Aka, a number of signals are transmitted at the same time. Each source transfers its signals in a specific frequency range. This reduces the probability of collision and overlapping.

## Token Ring
- Refers to the Multi Access Unit (MAU) that is used to build Local Access Networks (LAN).
- It's called a ring because the bits "*fly*" around in a circle, from node to node.
- Time Division Multiplexing
- Each node is gaurenteed to get acess to the network

## Ethernet
- Logically, an Ethernet connection is always a bus. This is what we refer to as a logical bus. Physically, it is usually a star design.
### Classic Ethernet
- Also called an Ethernet bus. A bus refers to one or more cables/wires that connect things from point A to point B.
- Not only is it slower than the alternative, it is also very fault intolerant. If one connection is disconnected, the entire network will go down.
### Switched Ethernet
- This refers to Ethernet connects that utilize a hub or a switch. Nowadays, we mostly use switches to overcome the problem of collisions and other effects on network speed. Due to the centralized wiring, we can bypass disconnected ports or cabling faults.
- The three parts of the Ethernet protocol which is called Carrier Sense, Multiple Access with Collision Detection (CSMA/CD):

	### Carrier Sense 
	- When a device connected to an Ethernet network wants to send data, it first checks to make sure that it has a carrier on which to send its data (usually a piece of copper cable (coaxial cable) connected to a hub or another machine).
	### Multiple Access
	- This means that all machines on the network are free to use the network whenever they like, so long as no one else is transmitting.
	### Collision Detection
	- A means of ensuring that when two machines start to transmit data simultaneously,  that the resultant corrupted data is discarded, and re-transmissions are generated at differing time intervals.