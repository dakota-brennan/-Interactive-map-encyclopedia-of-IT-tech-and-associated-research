IT VAULT
NETWORK CHAPTER
OSI PHYSICAL LAYER

<mark style="background: #D2B3FFA6;">Physical Layer (Layer 1)  </mark> 
#-1_physical_layer

	-nickname
The truck. Moves bits.

	-DEFINITION
This layer deals with the hardware of networks such as cabling. It defines the mechanical and electrical standards of interface devices and the types of cables used to transmit digital signals (e.g. #-optical_fiber,     #-coaxial_cable, #-wireless etc.)
@ https://www.techopedia.com/definition/24961/osi-protocols Technopedia 

The #physical_layer is responsible for the physical cable or wireless connection between network nodes. It defines the connector, the electrical cable or wireless technology connecting the devices, and is responsible for transmission of the raw data, which is simply a series of 0s and 1s, while taking care of bit rate control.
@ https://www.imperva.com/learn/application-security/osi-model/

The #physical_layer is concerned with transmitting raw bits over a communication channel. The design issues have to do with making sure that when one side sends a 1 bit, it is received by the other side as a 1 bit, not as a 0 bit. Typical questions are how many volts should be used to represent a 1 and how many for a 0, how many microseconds a bit lasts, whether transmission may proceed simultaneously in both
directions, how the initial connection is established and how it is torn down when both sides are finished, and how may pins the network connector has and what each pin is used for. The design issues deal largely with mechanical, electrical, functional, and procedural interface.
The #physical_layer describes some type of #-cabling_system as the <mark style="background: #FF5582A6;">transmission media</mark> . It also describes the #-network_topology and how the <mark style="background: #FF5582A6;">transmission media</mark> is to be distributed. Some examples include the #-bus , #-star , and #-ring_topologie 's .

	-PDU
Bit, symbol

	-FUNCTION
Transmission and reception of raw bit streams over a physical medium
@ https://en.wikipedia.org/wiki/OSI_protocols

