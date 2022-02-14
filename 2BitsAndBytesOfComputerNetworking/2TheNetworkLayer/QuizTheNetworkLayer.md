# The Network Layer


<br>

## Question 1

*An ARP broadcast is sent to the special MAC address ________.*

* **FF:FF:FF:FF:FF:FF**
* 00:00:00:00:00:00
* 255.255.255.255
*  92.168.0.1

> ARP broadcasts are used to ask all devices on a local area network if they're associated with a specific IP address

<br>

## Question 2

*The process of taking a large network and splitting it up into many individual and smaller subnetworks is known as ________.*

* encapsulation
* fragmentation
* **subnetting**
* routing

> Subnetting allows for much finer-grained controls of network sizes than the old class system could support

<br>

## Question 3

*Interior gateway protocols are used by routers in order to share information within a single ________.*x

* collision domain
* subnet
* **autonomous system**
* destination network

> An autonomous system is a group of networks all maintained by the same organization.

<br>

## Question 4

*Ranges of IP addresses that anyone can use for their internal networks are known as ______.*

* Subnet Masks
* Demarcation Points
* Autonomous Systems
* **Nonroutable Address Space**

> Non-routable address space can be used by anyone.

<br>

## Question 5

*Using logical operators, 1 AND 0 = _____.*

* True
* **False**
* 1
* 2

> Using the AND operator, the result is only 1, or true, if both sides are also 1, or true.

<br>

## Question 6

*A single octet in an IP address represents what range of decimal numbers?*

* 0-250
* **0-255**
* 0-155
* 1-255 

> Eight bits of data, or a single octet, can represent all decimal numbers from 0-255.

<br>

## Question 7

*What protocol communicates data between routers representing the edges of autonomous systems?*

* Distance-vector
* **Exterior gateway**
* Link state
* Interior gateway 

> Exterior gateway protocols are used to communicate data between routers representing the edges of autonomous systems.

<br>

## Question 8

*How many bits long is an IP address?*

* 256 bits
* 64 bits
* 8 bits
* **32 bits**

> IP addresses are 32-bit-long numbers made up of four octets, and each octet is normally described in decimal numbers.

<br>

## Question 9

*Which number cannot be represented by eight bits of data?*

* 128
* **436**
* 232
* 12

> Eight bits of data, or a single octet, can represent all decimal numbers from 0-255. 436 is beyond this limit.

<br>

## Question 10

*QoS services are protocols that allow routers to make decisions about which IP datagram may be more important than others. Which IP header field would QoS details be found?*

* Identification field
* **Service type field**
* Total length field
* Fragmentation offset field

> These 8 bits can be used to specify details about quality of service, or QoS, technologies. The important take away about QoS is that they’re services that allow routers to make decisions about which IP datagram may be more important than others.

<br>

## Question 11

*What is the purpose of an ARP response?*

* To send an ACK message to the broadcasting computer
* To prevent a flood of UDP packets
* **To let a computer broadcasting an ARP message know what MAC address to put into the destination hardware address field**
* To improve authentication security

> The node that wants to send data sends a broadcast ARP message to the MAC broadcast address which is all F’s. When the network interface  receives this ARP broadcast, it sends back what’s known as an ARP response. This response message will contain the MAC address for the network interface in question.



<br>

## Question 12

*Which octet of the subnet mask 255.255.255.0 will tell the router the corresponding host ID?*

* The middle two octets
* The first octet
* **The last octet**
* The first and last octet

> The size of a subnet is entirely defined by its subnet mask. So for example, with a subnet mask of 255.255.255.0, we know that only the last octet is available for host IDs, regardless of what the size the network and subnet IDs are.

<br>

## Question 13

*What will the operator 1 AND 1 return?*

* -1
* **1**
* 0
* 2

> The operator AND does what it sounds like it does. It returns true if both values are true. Therefore 1 AND 1 = 1, but 1 AND 0 = 0, 0 AND 0 = 0, and so on.

<br>

## Question 14

*How many possible host IDs do you always lose per network?*

* **2**
* 8
* 4
* 12

> You always lose two host IDs per network. So, if a /24 network has 2^8 or 256 potential hosts, you really only have 256 - 2 = 254 available IPs to assign.

<br>

## Question 15

*Which are a type of interior gateway protocol? (Check all that apply)*

* RDP (Remote Desktop Protocol)
* TFTP (Trivial File Transfer Protocol)
* **Link state routing protocols**

> Link state protocols get their name because each router advertises the state of the links of each of its interfaces. This information about each router is propagated to every other router on an autonomous system.
* **Distance-vector protocols**

> A router using a distance vector protocol basically just takes its routing table, which is a list of every network known to it and how far away these networks are in terms of hops. Then the router sends this list to every neighboring router, which is basically every router directly connected to it.