# Domain Name System (DNS)
- DNS is a Host Name to IP address Translation Service.
- It is an Application Layer Protocol.
- Previously, All the host name saved in host.txt File. It so complicated after increasing Internet and Websites.
- 6 Top level Domain include --> .com .org .biz .net .mil .edu
- DNS used to forward and reverse lookup.
- DNS servers are highly targeted by Hackers.
- It uses TCP port 53 and UDP port 53.
- Today, DNS support 13 root Name servers (A to M)
```
      Domain
        |
        |                      |------ .net
        |                      |------ .com
        |--------> Generic-----|         |
        |                      |------ .mil
        |                      |------ .edu
        |
        |
        |                      |------ .in
        |--------> Country-----|------ .uk
        |                      |------ .us
        |
        |
        |
        |--------> Inverse(IP to Domain Name Mapping)
```
## Name Space
- Namespace map each address to a unique Name.
- It has two types 1. Flat 2. Hierarchical
```
========================== Flat =============================
                             xyz.com
                                |
                                |
----------------------------------------------------------
|                      |                |                |
|                      |                |                |
riya.cloud           Amir.IT       vikas.admim      so on...


===================== Hierarchical ==========================

                            xyz.com
                               |
                               |
         ----------------------------------------
          |                   |                |        
          |                   |                |
        Cloud                IT              Admin
          |                   |                |
---------------    -----------------------   ------
|      |      |    |      |      |      |    |     |
Riya  Tulsi  Megha |      |      |      | Arjun Sakshi       
                   |      |      |      |    
                John    Adam   Harry   Roy
```  
## Hierarchy Of Name Server
1. **Root Name Server:** It is contacted by Name server that cannot resolve the name. It contacted by top level server if Name mapping is not known. IF gets mapping then it return the IP address to host.

2. **Top Level Server:** It is responsible for .com, .net,... etc and all top level country domain. They have information about Autherative Domain Servers and known names and IP addresses of each Authoratative Name Server for the second level domain.

3. **Authoratative Name Server:** It can be maintained by organization or service providers. In order to reach ccna.ak.in we have ask the root DNS server then it will point out to the top level DNS and then to Authoratative DNS which actually contains the IP address.

In the next day we will se about DHCP Server [Day 12](day12.md)