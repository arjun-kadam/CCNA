# DHCP (Dynamic Host Configuration Protocol)
- It automatically assign IP address to DHCP client (Host).
- It is based on client server model.
- DHCP works on Application Layer.
- Assigned IP range in DHCP is called Scope.
- BootP is the other method to allocate IP but MAC address must be entered manually in BootP Table.
- DHCP is dynamic BootP.
- It uses UDP port 67 & 68 at Transport Layer.

DHCP server can provide :
1. IP addresses 
2. Subnet Mask
3. Domain Name 
4. Default Gateway
5. DNS server address
6. WiNS Server Address

## Working Of DHCP - The DORA Process
- DORA --> Discover, Offer, Request, Acknowledgement.

1. **DHCP Discover** ***(Port 68):*** Host Machine UDP Broadcast to find locally available DHCP serve. Layer 2 Broadcast: FF:FF:FF:FF:FF:FF. Layer 3 Broadcast: 255.255.255.255.

2. **DHCP Offer** ***(Port 67):*** DHCP server to client in respose to DHCP discover with offer of configuration parameter (IP address of DHCP server, Offered IP address, MAC of client, Subnet Mask, Lease Length)

3. **DHCP Request** ***(Port 68):*** Client again broadcast to server after knowing the IP of DHCP server. DHCP request message asking for the offered IP addrerss and other information.

4. **DHCP Acknowledgement** ***(Port 67):*** Server to client with Configuration Parameter including commited network settings,


This is basic information about DHCP. We will see about ARP protocol on [Day 13](day13.md).