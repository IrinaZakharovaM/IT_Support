# The Transport and Application Layer

<br>

## Question 1

*Ports 1024-49151 are known as ______ ports.*

* system
* **registered**
* destination
* source

> Registered ports are used by less common applications.

## Question 2

*The most common example of a connection-oriented protocol is _____*

* UDP
* **TCP**
* IP

> Other examples of connection-oriented protocols exist, but TCP is, by far, the most common.

# Question 3

*HTTP is an example of a(n) ______ layer protocol.*

*transport
*data-link
* **application**
*network

>  There are lots of application layer protocols, but HTTP is one of the most common ones.

# Question 4

*Application layer data lives in the _____ section of the transport layer protocol.*

* **data payload**
*header
*footer
*flags

> The payload section of one layer contains the content of the layer above it.

# Question 5

*The concept of taking traffic that’s all aimed at the same node and delivering it to the proper receiving service is known as _________.*

* multiplexing
* **demultiplexing**
* routing
* ncapsulation

> Demultiplexing allows traffic intended for many different services to be delivered to the same node.

# Question 6

*A network has the ability to direct traffic toward all of the receiving services. What provides this ability in the transport layer?*

* **Multiplexing**
* Socket address
* File Transfer
* Demultiplexing
 
>  Multiplexing in the transport layer means that nodes on a network have the ability to direct traffic toward many different receiving services.

# Question 7

*A Transmission Control Protocol (TCP) connection is in working order and both sides can send each other data. What is the TCP socket state?*

* SYN_RECEIVED
* LISTEN
* SYN_SENT
* ESTABLISHED

> The ESTABLISHED state means that the TCP connection is in working order and both sides are free to send each other data.

# Question 8

*Which field in a Transmission Control Protocol (TCP) header is chosen from ephemeral ports?*

* Acknowledgement number
* Destination port
* Sequence number
* **Source port**

> A source port is a high-numbered port chosen from a special section of ports known as ephemeral ports.

# Question 9

*A communication between two devices is over the maximum limit of an ethernet frame size. The Transmission Control Protocol (TCP) splits up the data into segments. Which field in the header helps keep track of the many segments?*

* Checksum
* **Sequence number**
* Urgent pointer
* Acknowledgement number

> The sequence number is used to keep track of where in a sequence of TCP segments that the packet is expected to be.

# Question 10

*A connection, at which layer, implies that every segment of data sent is acknowledged?*

* Data link
* Network
* **Transport**
* Application

> A connection at the transport layer implies that every segment of data sent is acknowledged.

# Question 11

*Connection-oriented protocols protect against dropped data by forming connections and using what type of constant stream?*

* **Acknowledgements**
* Checks
* Approvals
* Verifiers

> Connection-oriented protocols protect against dropped data with a constant stream of acknowledgements.

# Question 12

*When is using the Transmission Control Protocol (TCP) most appropriate?*

* When you visit a news website
* When you are streaming a video.
* **When you make a phone call**
* When you are listening to the radio.

>  Phone calls require a connection-oriented protocol, such as TCP.

# Question 13

*What does a value of one in an ACK control flag represent?*

* There is one more packet to be transmitted.
* There is one packet to deliver.
* It is the first transmission.
* **The acknowledgement number field should be examined.**

> A value of one in the ACK flag field means that the acknowledgement number field should be examined.

# Question 14

*Which Transmission Control Protocol (TCP) flag is used to make sure the receiving end knows how to examine the sequence number field?*

* **SYN**
* PSH
* URG
* ACK

> The SYN flag is used to make sure the receiving end knows how to examine the sequence number field.