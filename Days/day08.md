# Addressing

Addressing used to idetify device and network uniquely.

- There are two types of Addressing 1) Logical 2) Physical

- Logical --> IP 
- Physical --> MAC
```
               Addressing
                 /   \
                /     \
               /       \
              /         \
             /           \
        Physical       Logical
           |         (Public & Private)
           |            /   \
           |           /     \
          MAC        IPv4   IPv6
```

## What is MAC ?
- Media Access Control / Mobile Access Control / Physical Address...
- MAC is globally Unique
- MAC is 48 bits Address (6 bytes)
- MAC represented in Hexadecimal Format
```
34-AB-CD-FE-69-49 ---> Laptop/PC
34:AB:CD:FE:69:49 ---> Mobile
34AB.CDFE.6949 ------> Cisco Routers
```
Above all MAC are same but Representation is Different.


- From 48 bits 24 bits are distributed by OUI(Organiztion Unique Identifier) and other 24 bits are dicided by Vendor like HP, Asus, Apple....

```
                         48 Bits
                            |
                            |
    -----------------------------------------------
   |                                               | 
   |                                               |
24 bits                                      Vender Specific
Organiztion Unique                     (HP, Asus, DELL...etc)
Identifier(OUI)


```
- FF:FF:FF:FF:FF:FF --> This MAC is used to Broadcast and resolve host MAC.

This is for Today In Next Day we will see IP addressing in detail on [Day 9](day09.md)
