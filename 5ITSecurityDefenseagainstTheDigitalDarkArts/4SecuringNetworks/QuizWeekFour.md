# Week Four Practice Quiz

## Question 1

*What traffic would an implicit deny firewall rule block?*

* Nothing unless blocked
* Inbound traffic
* Outbound traffic
* **Everything not allowed**

> Implicit deny means that everything is blocked, unless it's explicitly allowed.

## Question 2

*The process of converting log entry fields into a standard format is called _______.*

* Log auditing
* **Log normalization**
* Log analysis
* Log encryption

> Normalizing logs is the process of ensuring that all log fields are in a standardized format for analysis and search purposes.

## Question 3

*A ______ can protect your network from DoS attacks.*
 
* Dynamic ARP Inspection
* **Flood Guard**
* DHCP Snooping
* IP Source Guard

> Flood guards provide protection from DoS attacks by blocking common flood attack traffic when it's detected.

## Question 4

*Using different VLANs for different network devices is an example of _______.*

* **Network Separation**
* Implicit Denial
* Remote Access
* Network Encryption

> Using VLANs to keep different types of devices on different networks is an example of network separation.

## Question 5

*How do you protect against rogue DHCP server attacks?*

* Flood Guard
* IP Source Guard
* Dynamic ARP Inspection
* **DHCP Snooping**

> DHCP snooping prevents rogue DHCP server attacks. It does this by creating a mapping of IP addresses to switch ports and keeping track of authoritative DHCP servers.

## Question 6

*What does Dynamic ARP Inspection protect against?*

* **ARP Man-in-the-middle attacks**
* IP Spoofing attacks
* DoS attacks
* Rogue DHCP Server attacks

> Dynamic ARP Inspection will watch for forged gratuitous ARP packets that don't correspond to the known mappings of IP addresses and MAC address, and drop the fake packets.


## Question 7

*What kind of attack does IP Source Guard protect against?*

* Rogue DHCP Server attacks
* ARP Man-in-the-middle attacks
* DoS attacks
* **IP Spoofing attacks**

> IP Source Guard protects against IP spoofing. It does this by dynamically generating ACLs for each switch port, only permitting traffic for the mapped IP address for that port.


## Question 8

*A reverse proxy is different from a proxy because a reverse proxy provides ______.*

* Authentication
* **Remote Access**
* DoS protection
* Privacy
 
> A reverse proxy can be used to allow remote access into a network.

## Question 9

What underlying symmetric encryption cipher does WEP use?

* RSA
* AES
* DES
* **RC4**
 
> WEP uses the RC4 stream cipher.

## Question 10

*What key lengths does WEP encryption support? Check all that apply.*

* 40-bit 
* **64-bit**
* **128-bit**
* 256-bit

> WEP supports 64-bit and 128-bit encryption keys.

## Question 11

*What's the recommended way to protect a WPA2 network? Check all that apply.*

* Hide the SSID
* **Use a unique SSID**
* **Use a long, complex passphrase**
* Use WEP64

> Because the SSID is used as a salt, it should be something unique to protect against rainbow table attacks. A long, complex password will protect against brute-force attacks.

## Question 12

*If you're connected to a switch and your NIC is in promiscuous mode, what traffic would you be able to capture? Check all that apply.*

* No traffic
* **Broadcast traffic**
* **Traffic to and from your machine**
* All traffic on the switch

> Since you're connected to a switch, you'd only see packets that are sent to your switch port, meaning traffic to or from your machine or broadcast packets.

## Question 13

*What could you use to sniff traffic on a switch?*

* Promiscuous Mode
* DHCP Snooping
* **Port Mirroring**
* Network hub

> Port mirroring allows you to capture traffic on a switch port transparently, by sending a copy of traffic on the port to another port of your choosing.

## Question 14

*What does tcpdump do?*

* Generates DDoS attack traffic
* Handles packet injection
* **Performs packet capture and analysis**
* Brute forces password databases

> tcpdump captures and analyzes packets for you, interpreting the binary information contained in the packets and converting it into a human-readable format.

## Question 15

*Compared to tcpdump, wireshark has a much wider range of supported _______.*

* **Protocols**
* Languages
* Packet sizes
* Packet types

> Wireshark supports a very wide range of various networking protocols.

## Question 16

*A Network Intrusion Detection System watches for potentially malicious traffic and _______ when it detects an attack.*

* **Triggers alerts**
* Shuts down
* Blocks traffic
* Disables network access

> A NIDS only alerts when it detects a potential attack.

## Question 17 

*What does a Network Intrusion Prevention System do when it detects an attack?*

* It triggers an alert.
* It attacks back.
* **It blocks the traffic.**
* It does nothing.

> An NIPS would make adjustments to firewall rules on the fly, and drop any malicious traffic detected.