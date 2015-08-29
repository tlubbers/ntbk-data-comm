# Chapter 1 - Introduction

## Data Communications

*Data communications* are the exchange of data between two devices via some form of transmission medium such as a wire cable.

Data communication systems rely on *four important things*.

1. *Delivery.* The system must deliver data to the correct destination, and correct user.

2. *Accuracy.* The system must deliver the data accurately, without any inconsistencies.

3. *Timeliness.* The system must deliver data in a timely manner. Think about netflix lagging.

4. *Jitter.* Jitter refers to the variation in the packet arrival time, or everything incoming should remain incoming at the same rate throughout the entirety of the transfer.

### Connection types

Data Systems can be configured as *point-to-point* or *multipoint*. Multipoint has the advantage of being cheap and easy to install.

### Components of a Data Comm System

* Message
* Sender
* Receiver
* Medium
* Protocol

A *protocol* is a set of rules that govern data communications. It represents an agreement between the communicating devices. Without a protocol, two devices may be connected but not communicating, just as a person speaking French cannot be understood by a person who speaks only Japanese.

### Data Flow

There are three ways data can flow, simplex (one-way) - half-duplex(two-way, only one at a time) - full-dupex(two way-always).

## Networks

A set of devices connected and capable of communicating. befined by performance, reliability, and security.

### LAN and WAN

- *LAN* defined by geometric size of network
- *WAN* world wide

### Switches

A switched network is a network where a switch connects at least two links together. There are two types.

### Standards

- *Maturity*
- Proposed Standard: Stable, well understood, and people want it.
- Draft Standard: Once proposed gets indepentendantbly implemented twice, its a draft standard. Minor issues are resolved and then its upgrade to Internet standard.
- Internet Standard: ...see above
- Historical: significant only from historical stand  point
- Experimental: not neccesarily a good idea
- Informational: tutorialish

 - *Requirement Levels*
 - Required
 - Recommended
 - Elective  (nt recommended but its okay if you need it)
 - Limited use (only in crazy ciurmustances)
 - Not recommended

### Topology

#### Mesh
- Every computer is linked to every other computer.
- Requires n(n-1)/2 links.
- Very redundant
- Expensive, confusing

#### Star
- Each computer links to a hub
- n links are needed
- Less expensive, if one device fails, only that device is affected.

#### Bus
- Every device connects to a bus with a drop line.
- Easy to install
- Difficult reconnection, hard to add new devices

#### Ring
- Every device is connected point to point to the two machines next to it, ina ring.
- Signals are repeated along the ring between devices
- A break in a simple ring breaks everything but its easy to configure


