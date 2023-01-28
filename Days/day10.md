# Subnetting
## What is Subnetting ?
- Network within a network or logically division of IP address.
## Problems Before subnetting
- In routers every interface has Unique net-ID.
- If we connect 50 computer to any interface of router and give net-ID 10.0.0.0 then we can use only 50 IP addresses. This results that other remaining IP's will be wastage.

### How to get subnet mask of any IP ?
- If given IP is 115.10.10.20
- Find Class Of IP, Here Class A IP address.
- Then Get Network ID of given IP, Here 115.0.0.0
- Convert it into binary and set all network bits to `1`.
- Again convert Binary to Decimal, That's the Subnet Mask.

```
    IP --> 115.10.10.20
    Class --> A
    Net-ID --> 115.0.0.0
    Binary --> 01110011 00000000 00000000 00000000
    
    Set Nework Bit To 1 --> 11111111 00000000 00000000 00000000
    Again Decimal ---> 255.0.0.0 

    255.0.0.0 is Subnet Mask Of IP 115.10.10.20

```

# Supernetting
- Combining two or more IP networks/ IP subnetwroks with a common subnet mask or CIDR.
- It reduces Routing Table Entries.
## Conditions For Supernetting
- All IP shoild be contiguous in Nature.
- Size of all the Network should be Same .
- Network ID should be divisible by total number of hosts.

This is Introductory Topic on Subnetting and Supernetting If you want to learn more about it you can find Tutorials on YouTube. Lets Meet on [Day 11](day11.md) With DNS.