# Networking Devices.

## What is networking devices ?
- Networking Devices are responsible for establish connection between twob devices.
- I am going to explain about following devices more.

# Hub
- Layer-1 Device
- Works on electrical signal or bits.
- It is Half duplex.
- Cannot Store MAC.
- Always Broadcast
- Single Collision Domain.
- LAN Device 
- It is not Intelligent Device.
<img src="Images/hub.jpg?raw=true" alt="Hub Diagram">

# Repeater 
- It regenerate your signal.
- cable can transmit upto 185m signal then we have to use Repeater to regenerate signal.
- It also known as Active Hub.

<img src="Images/repeater.jpg?raw=true" alt="Repeater Diagram">

# Bridge
- It is Intelligent Device.
- Layer 2 Device
- Use to connect multiple network segment or LAN segment.
- Bridge inspect incoming traffic and decide whether to forward or reject. It check source and destination MAC adress.
- Bridges reduce the amount of traffic on a LAN by dividing it into two segments.
- It has two collion Domain.
<img src="Images/bridge.png?raw=true" alt="Bridge diagram">

# Switch
- Layer 2 Device.
- Full duplex
- Maintain CAM Table (Content Accessible Memory)
- First time broadcast and then unicast & multicast
- Every port of Switch is separate collision Domain
- Switch has one broadcast domain.
- Switch can be 8/16/24/48 Ports.
- If we change the device then it will again broadcast message and then it will update the CAM Table.
<img src="Images/switch.png?raw=true" alt="Switch Diagram">

# Router
- Layer 3 Device.
- WAN Device (Rarely use in LAN)
- Use to connect two or more Networks
- Hub, Switch and Bridge are Networking Devices But <b> Router is InterNetworking Device</b> becuase it communicate between two different networks.
- We can't connect our devices directly to router. we need to connect devices to switch then switch is connected to router.
- Router manintain Routing Table in that it maintain port & Network ID's.
- In Router, every port send data in the form of packets.
- Routers can have 2/4/8 Ports
-  Fast 10Mbps/100Mbps/1GBps
<img src="Images/router.png?raw=true" alt="Router Diagram">

# Gateway
- A Gateway is a connecting device used ton connect remote networks with host netwok.
- It act as entry or exit point of networks.
- Gateway operates at Application Layer.

## Final Words

Hope You Undersatnd the concept of Networking Devices. If you want to improve this guide then contribute. Let's Meet on next Day with Network Topology [Day 6](day06.md)