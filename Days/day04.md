## TCP/IP Model
- TCP - Transmission Control Protocol.
- IP - Internet Protocol.
- This model is practical and implemented.
- In various books their are 5 layers are explained, but we will see only 4 layers implentation.
### Why different books have different no. of layers?? 
- In term of OSI model, this model is not implemented because the developers of OSI model are focused on theoritical and paper work. but at that time web need any type of decentralised network protocol.

- But TCP/IP developers first developed model and and it becomes very popular. After that many professor write books on TCP/IP model according to their study so in books we saw different no. of layers.
### Need of TCP/IP
1. How data is trasnmitted across network.
2. How data should be formatted so other network system can understand it.

### Two key feature that support decetraliation in data transfer
1. <b>Find Node Verification: </b> Two endpoint of any data transfer are responsible for making sure it was successfully.

2. <b>Dynamic Routing :</b> End nodes can transfer data over multiple paths and the network choose the best path for individual data transfer.

### Network Issues: 
1. Addressing
2. Routing
3. Name Resolution
4. Flow & Error Control
5. Interportability

### TCP/IP Explained 
<img src="Images/TCP_IP.jpg?raw=true" alt="TCP/IP Model">

### TCP
1. TCP is Connection oriented.
2. Data transfer and receive acknowledgement is present.

   eg. If user A sneding "5" data packets to user B, if packet no.4 is not received then user B gives acknowledge to user A to retransmit data packet.
3. Used For non-real time data transfer.
4. Slow in comparision to UDP.
5. It is reliable.

### IP
1. Sender and Reciever has IP address.
2. IP contains Routing Information.

Hope You Undersatnd the basic concept of TCP/IP Model. If you want to improve this guide then contribute. Let's Meet on next Day with Network Devices [Day 5](day05.md)

