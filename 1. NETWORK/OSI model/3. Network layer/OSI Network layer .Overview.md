IT VAULT
NETWORK CHAPTER
OSI NETWORK LAYER

<mark style="background: #ABF7F7A6;">Network Layer (Layer 3)</mark> 

	-nickname
Mailroom guy. IP addressing/routing.

The network layer has two main functions. One is breaking up segments into network packets, and reassembling the packets on the receiving end. The other is routing packets by discovering the best path across a physical network. The network layer uses network addresses (typically Internet Protocol addresses) to route packets to a destination node.
@ https://www.imperva.com/learn/application-security/osi-model/

The network layer controls the operation of a sub-net, provides routing, congestion
control and accounting. The network layer provides both connectionless and
connection-oriented services. A key design issue is determining how packets are
routed from source to destination. Routes can be based on static tables that are within
the network and rarely change. They could also be determined at the start of each
conversion. Finally, they could be highly dynamic, being newly determined for each
packet to reflect the current network load. It is up to the network layer to allow
heterogeneous networks to be interconnected. The IP protocol resides in this layer. All
routers in the network are operating at this level.
If too many packets are present in the sub-net at the same time, bottlenecks will form.
The network layer helps to control this congestion. An accounting function is built into
the network layer to ensure that the number of bits sent is the number of bits received.
Controls over network connections, logical channels, segmenting and sequencing, and
data flow can be placed in this layer.

	-PDU
Packet

	-FUNCTION
Structuring and managing a multi-node network, including [addressing](https://en.wikipedia.org/wiki/Address_space "Address space"), [routing](https://en.wikipedia.org/wiki/Routing "Routing") and [traffic control](https://en.wikipedia.org/wiki/Network_traffic_control "Network traffic control")
@ https://en.wikipedia.org/wiki/OSI_protocols


LINK LIST
