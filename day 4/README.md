✅What is a Subnet?
A subnet (short for subnetwork) is a smaller network within a larger network. It divides an IP network into smaller parts to:

Improve network performance

Increase security

Better manage traffic

For example, if a company has the network 192.168.1.0/24, it can be divided into smaller subnets like:

192.168.1.0/25 (first half)

192.168.1.128/25 (second half)

✅ What is a Network?
A network is a group of connected devices (computers, printers, servers, etc.) that can communicate and share resources. This communication can be:

Local (e.g., in an office—LAN)

Global (e.g., the internet)

✅ What is an IP Address?
An IP address (Internet Protocol address) is a unique number assigned to every device on a network. It's used to identify and locate devices.

There are two types:

IPv4: Example → 192.168.1.1

IPv6: Example → 2001:0db8:85a3:0000:0000:8a2e:0370:7334

✅ What is a MAC Address?
A MAC address (Media Access Control address) is a hardware address built into the network interface card (NIC) of a device.

Format: 00:1A:2B:3C:4D:5E

It's permanent and unique to the device

Used in LANs for identifying devices at the data link layer (Layer 2 of OSI model).

✅ TCP vs UDP (Types of Protocols)
Both TCP and UDP are transport layer protocols (Layer 4 of OSI) used for sending data across networks.

Feature	TCP	UDP
Full Form	Transmission Control Protocol	User Datagram Protocol
Connection Type	Connection-oriented (reliable)	Connectionless (faster)
Speed	Slower due to error-checking	Faster, no guaranteed delivery
Use Cases	Web (HTTP/HTTPS), Email, FTP	Streaming, VoIP, DNS, Gaming
Reliability	Guarantees delivery, order	No guarantee of delivery/order

✅ What is IPv4 and IPv6?
These are versions of the Internet Protocol used to assign addresses.

Feature	IPv4	IPv6
Address Length	32-bit	128-bit
Format	Decimal (e.g., 192.168.0.1)	Hexadecimal (e.g., 2001:db8::1)
Address Count	~4.3 billion	Virtually unlimited
Deployment	Still widely used	Growing, especially for modern tech

✅ What is Port Forwarding (Forward Port)?
Port forwarding allows external devices to access services on a private network. It maps an external port to an internal IP and port.

For example:

External request to your public IP at port 8080 → forwarded to internal device 192.168.1.10:80

Used for:

Hosting game servers

Running web servers at home

Remote access to a camera or computer
