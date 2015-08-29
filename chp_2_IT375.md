# Chapter 2 - Network Models

## Protocol Layering
Protocols are layered, each layer having its own set of functions, which makes it easy to design each protocol layer independantly. Makes designing and modifying the overall protocol much easier.

## TCP/IP Protocol Suite
The TCP/IP Protocol Suite is the computer networking model and set of communications protocols used on the Internet and similar computer networks. TCP/IP is used for the name because TCP/IP Protocols are the most important protocols in the suite.

*Encapsulation* begins at the application layer, passes it to the transport layer which adds it's header, then to network which adds its header, and so forth. Then when data gets to the destination, each layer removes (*decapsulates*) its header info until it gets to the application layer. Figure 2.8 on page 41 visualizes encapsulation well.

*Addressing*  Every time data moves from hop

### TCP/IP Layers

1. Application

2. Transport

3. Network:

4. Data link: The data-link layer is responsible for moving a frame through the link that the router has chosen.

5. Physical: In charge of moving bits from hop to hop. Functions include conversion of bits to signal, synchronizing bits, transmitting the signal, knows how to use the active physical topology, figures out the line configuration, etc.

## OSI Model
