# Week 2

## Payload
- Refers to the information that you're sending from sender to receiver.
	- Ex. A telephone call between two people: the payload is between two people. A telephone call between three people: the payload increases, since there is a new receiver.

## Switching
- Refers to the method that is used to establish connections between nodes within a network. It's the information about a certain communication (i.e who the sender is and who the receiver is).
	- Ex. Back in the old days, switching was done manually: an operator would ask who you wanted to send a call to and they would manually plug in a connection (with you and the receiver) to the switchboard.

## Trunk line
- Refers to the bridge that connects switchboards between different standard local circuits (or central office).
	- Ex. A trunk line is connected between Tallahassee and Orlando to connect a sender and a receiver enacting in a long distance phone calls.
	
## Sampling
- Refers to the reduction of a continuous-time signal to a discrete-time signal. A common example is the conversion of a sound wave (a continuous signal) to a sequence of samples (a discrete-time signal).
- To increase quality, we increase the number of times we sample. In music, you can see this in increasing the bit-rate. 
	- Ex. 8-bit sampling is of a lower quality than 32-bit sampling. The payload is higher, as we are increasing the amount of information sent. This results in larger file sizes.

## Nyquist-Shannon sampling
- ** *I talked to him after class, we don't have to actually know this but it might show up as an extra credit question!* **
- To faithfully reproduce the human voice it requires a sampling rate of 4000 cycles x 2 samples for each hertz x 8 bits for each sample. Simple mathematics tells us that this totals a 64,000 bytes (more commonly written as 64kb) sampling rate per second. Due to modern compression algorithms and techniques, we are able to substantially lower this number.