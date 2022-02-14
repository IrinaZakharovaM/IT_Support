# Troubleshooting and the Future of Networking

**Latest Submission Grade: 81.25%**

<br>

## Question 1

*ICMP stands for ________.*

* **Internet Control Message Protocol**
* Internet Client Message Protocol
* Interactive Control Message Protocol
* Internet Control Mail Protocol

> ICMP is used to deliver messages about network errors.

<br>

## Question 2

*While in an interactive nslookup session, you'd use the ______ keyword to change the DNS server you're using.*

* **server**
* client
* FQDN
* DNS

>  Issuing a server keyword, followed by a DNS server, will change what server you're using for resolution attempts.

<br>

## Question 3

*The IPv6 loopback address is _____.*

* 127.0.0.1
* 0000:0000:0000:0000:0000:0000:0000:0000
* **0000:0000:0000:0000:0000:0000:0000:0001**

> The IPv6 loopback address is a great example of how IPv6 address compaction works.

<br>

## Question 4

*IPv6 addresses beginning with FE80:: are used for ______.*

* public multicast
* anycast
* Network Address Translation
* **link local unicast**

>  Link-local unicast is used for IPv6 nodes to get their network configuration, much like DHCP.

<br>

## Question 5

*The IPV4 mapped address space within IPv6 always starts with _______ zeroes.*

* 32
* 64
* **80**
* 128

> 80 zeroes, followed by 16 ones, followed by the IPv4 address itself it how the IPv4 mapped address space works.

<br>

## Question 6

*Traceroute uses UDP packets on which of the following operating systems? Check all that apply.*

* Windows 10
* Windows 7
* **Linux**
> On Linux and macOS, traceroute sends UDP packets to very high port numbers.
* **Mac OS**
> On Linux and macOS, traceroute sends UDP packets to very high port numbers.

<br>

## Question 7

*A tech uses the netcat tool on a Linux system. Of the choices, which has proper syntax?*

* **nc google.com 80**
* nc google.com -z
* nc google.com
* nc -v 80

> The nc command requires that a host and a port are included.

<br>

## Question 8

*Which of these addresses is an Internet Protocol (IP) v4 loopback address?*

* 8.8.8.8
* 1.2.3.4
* 192.168.1.1
* **127.0.0.1**

> A loopback address points to itself and is used for troubleshooting purposes.

<br>

## Question 9

*Which option is NOT provided with cloud storage?*

* Security
* Availability
* Accessibility
* **Physical hardware**

>  Cloud storage is Internet based disk space. Optional local physical disk space is provided by the user.

<br>

## Question 10

*Which Internet Protocol (IP) v6 header field is used to determine the quality of service level for a datagram?*

* Version
* Next header
* Payload length
* **Flow label**

> The flow label field is used in conjunction with the traffic class field for routers, to make decisions about the quality of service level for a specific datagram.

<br>

## Question 11

*The first field of an Internet Control Message Protocol (ICMP) packet specifies the message type. Which choices represent message type examples? Check all that apply.*

* **Destination unreachable**
> The type field specifies the message type. A code field further breaks down the message type to be more specific.
* Destination port unreachable
* **Time exceeded**
> The type field specifies the message type. A code field further breaks down the message type to be more specific.
* Destination network unreachable

<br>

## Question 12

*When registering a new domain name, either the registrar's servers or self-owned servers can be used as name servers. What function will the name servers provide for the domain?*

* **Authoritative**
* Address reservation
* Domain transfer
* Error recovery

> An authoritative name server is responsible for a Domain Name System (DNS) zone.

<br>

## Question 13

*Which addresses represent valid local loopback addresses? Check all that apply.*

* **::1**
> The Internet Protocol address ::1 is known as a v6 local loopback address.
* ::0
* 255.255.255.255
* **127.0.0.1**
> The Internet Protocol address 127.0.0.1 is known as a v4 local loopback address.

<br>

## Question 14

*Internet Protocol (IP) v6 addresses are written out in which format?*

* **8 groups of 16 bits**
* 8 groups of 12 bits
* 4 groups of 16 bits
* 6 groups of 32 bits

> IPv6 addresses are usually written out as 8 groups of 16 bits each. Each of these groups is further made up of 4 hexadecimal digits.

<br>

## Question 15

*When the ping command is used, output is similar across operating systems. Which two values are displayed as part of the output? Check all that apply.*

* Port number
* **Message byte size**
> Every line of output will generally display how large the message is in bytes.
* **Round-trip time**
> Every line of output will generally display how long it took for the round-trip communications.
* Gateway address

<br>

## Question 16

*What size is an Internet Protocol (IP) v6 payload field?*

* 20-bit
* 8-bit
* 32-bit
* **16-bit**

> The payload length field is a 16-bit field that defines how long the data payload section of the datagram is.