# IP Addressing 
We will see IPv4 Addressing in this guide.
## IPv4 Address
- It is 32-bit address.
- Total 4 octect(1 octect = 8 bits)
- One octect range from 0-255 Max
- IP Address ---> Network ID + Host ID
```
==========================================================
|     198     |     168     |    39       |    240       |
========================================================== 
<---8-bit----> <---8-bit---> <----8-bit--> <----8-bit---->
```
### Classes
- Class A --> 1.0.0.0 to 126.0.0.0
- Class B --> 128.0.0.0 to 191.255.0.0
- Class C --> 192.0.0.0 to 223.255.255.0
- Class D --> 224 to 239
- Class E --> 240 to 255
- Loop Back Address --> 127.0.0.0

### Network ID
```
N = Network ID   H = Host ID
Network Bit ==> 1   Host Bit ==> 0

=====================================
|    N   |    H   |    H   |    H   | -- > Class A
===================================== 

=====================================
|    N   |    N   |   H    |    H   | ----> Class B
===================================== 

=====================================
|    N   |    N   |   N    |    H   | ----> Class C
===================================== 

```
### Example 
If you want extract Network ID of Any IP then
- First find class of IP
- Set Host bit to 0
```
Given IP : 115.0.0.15
           196.10.10.10
Then,
Network ID : 115.0.0.0
             196.10.10.0
```
I hope you will understand the concept of IP addressing. Next we will see Subnetting on [Day 10](day10.md)