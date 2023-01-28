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
Updating Soon.........