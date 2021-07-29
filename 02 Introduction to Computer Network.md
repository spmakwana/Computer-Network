# Unit 01 - Introduction to - Computer Network

## Table of Contents

- [What is Computer Network?](#what-is-computer-network-)
- [Overview of computer network](#overview-of-computer-network)
- [Types of Computer Network](#types-of-computer-network)
  * [LAN](#lan)
  * [MAN](#man)
  * [WAN](#wan)
  * [Wireless Network](#wireless-network)
- [Usage of computer network](#usage-of-computer-network)
- [Network Architecture](#network-architecture)
  * [Centralized Network (Client Server Network)](#centralized-network--client-server-network-)
    + [Advantages](#advantages)
    + [Disadvantages](#disadvantages)
  * [Peer to Peer Network](#peer-to-peer-network)
    + [Advantages](#advantages-1)
    * [Disadvantages](#disadvantages-1)
- [Line Configuration](#line-configuration)
  * [Point to Point Configuration](#point-to-point-configuration)
  * [Multipoint Configuration](#multipoint-configuration)
    + [Spatial Sharing](#spatial-sharing)
    + [Temporal (Time) Sharing](#temporal--time--sharing)
- [Network Server](#network-server)
- [Types of Network Server](#types-of-network-server)



# What is Computer Network?
A computer network is a group of two or more interconnected computer systems. You can establish a network connection using either cable or wireless media. 
# Overview of computer network 	
* Computer networking or data communication is a most important part of the information technology.
* Today every business in the world needs a computer network for smooth operations, instant communication and data access.
* A computer network is comprised of connectivity devices and components and software, to share data and resources between two or more computers.
* The key devices involved that make the infrastructure of a computer network are Hub, Switch, Router, Modem, Access point, LAN card and network cables.

# Types of Computer Network
There are different types of a computer network such as LAN, MAN, WAN and wireless network. 
## LAN
LAN stands for local area network and a network in a room, in a building or a network over small distance is known as a LAN.
## MAN
MAN stands for Metropolitan area network and it covers the networking between two offices within the city. 
## WAN
WAN stands for wide area network and it cover the networking between two or more computers between two cities, two countries or two continents.
## Wireless Network
Wireless network is generally span in limited area like house or building. But sometime using special hardware it can span on very large area.
# Usage of computer network
* Network help us to connect multiple computer together to send and receive information from one computer to another.
* Network helps you to share common services like printer, scanner etc.
* Can be used to send/receive emails
* Usage of computer network
* The best example of computer network is the Internet.
* Now a days network is used everywhere from home to multinational companies to run the daily task and functioning.
* Resource Sharing
  * Hardware Resource Sharing
  * Software Resource Sharing
* Information Sharing
  * Easy accessibility from anywhere
  * Search Capabilities (internet)
* Communication
  * Email, Messaging, etc.
* Remote Computer
* Distributed Processing / Computing
# Network Architecture
Network architecture can be categorized into two categories.

* Centralized Network (Client Server Network)
* Peer to Peer Network

## Centralized Network (Client Server Network)

- It is also known as client-server computing. 
- In this type of system, multiple computers are joined to one powerful computer (Generally a mainframe computer).
- Main central computer is called server, and other connected computers are known as client.
- The server or mainframe computer has huge storage and processing capabilities.
- Client PC is thin client with no or very limited computing capacity.
- The computers that are connected to the mainframe or server are called Clients or Nodes.
- These nodes are not connected to each other; they are only connected to central server.

![Client Server Network](https://user-images.githubusercontent.com/4832630/127463329-1df7bb51-d3c1-4bd3-a926-521ca3ef5dcf.png)

Image Source: https://logisticsmgepsupv.wordpress.com/2019/05/13/centralized-distribution-network/

### Advantages

- Reduced costs: In centralized computer network we can only have one single powerful computer which serves the needs (processing and storage) of all the client, so client can have less powerful CPU or also can have no CPU at all.
- Less Equipment: Less equipment is needed, may not need all equipment for all the computers in network, because some resources can be served by central server.
- Simplicity: Architecture of Centralized network is very simple, as all clients are connected to a single central server.
- Easy Maintenance: Maintenance is easy as architecture is simple and if something goes wrong, then finding the fault is also easier.

### Disadvantages

- Single point of failure – If Server fails whole network goes down and stopped working.

## Peer to Peer Network

- In Centralized network most computers of the network are controlled by main server.
- In Peer to Peer network, there is no central server and no connected clients.
- All computers has almost same computing and storage capacity.
- In peer to peer network, computer does not rely on server for computing or storage as all computer has own computing power and storage

![991px-P2P-network svg](https://user-images.githubusercontent.com/4832630/127473164-403e3415-a482-4e32-b322-d098e83d8941.png)

Image Source: https://upload.wikimedia.org/wikipedia/commons/thumb/3/3f/P2P-network.svg/991px-P2P-network.svg.png

### Advantages

- Computer on network does not have rely on server for computing power or storage
- No single point of failure as it is not controlled by one single server.

### Disadvantages

- Computers are not as powerful as Central Server, so sometimes processing capabilities is less compared to centralized network.
- Finding a fault can be difficult sometime as sometimes architecture of network can be complex.

# Line Configuration

- Line configuration refers to the way two or more communication devices attached to a link.
- Link Configuration is also referred as a connection.
- A Link is the physical communication pathway that transfers data from one device to another.
- For communication to occur, two devices must be connected in same way to the same link at the same time.
- There are two possible line configurations.
  - Point-to-Point
  - Multipoint

## Point to Point Configuration

- In point to Point configuration, there is a dedicated link between two devices.
- Link can be of actual wire/cable to between two devices or can be a dedicated wireless channel. For example microwave link, satellite link, infrared link etc.
- Most of the time wired link is used to connect the devices in point to point configuration. But rarely wireless connection is also used. 
- Entire Capacity of the channel is reserved for the transmission between those two devices.
- This configuration is considered to be one of the easiest and most conventional network configuration.
- E.g. Two PC are connected with a LAN cable.
- E.g. Two phones are connected via Bluetooth.

![Point to Point Configuration](https://user-images.githubusercontent.com/4832630/127472788-f4627696-6f08-4f91-a618-692a79151b38.png)

Image Source: http://mucins.weebly.com/21-line-configuration.html

## Multipoint Configuration

- Multipoint configuration is also known as multiline configuration.
- In multipoint one or more than two devices share a single line (link) of the channel for transmission of data.
- Basically, same channel is shared by multiple devices.

![Multipoint Configuration](https://user-images.githubusercontent.com/4832630/127473023-df51d2a4-a4ed-455b-b215-30c827b3a86e.png)
Image Source: http://mucins.weebly.com/21-line-configuration.html

- Two possibilities in multipoint line configuration
  - Spatial Sharing
  - Temporal (Time) Sharing

### Spatial Sharing

- If several devices share the link simultaneously, it called spatially shared line configuration.
- Here each devices don’t get full bandwidth of channel for data transfer as same channel is shared by all devices.

### Temporal (Time) Sharing

- In this method data sharing is done in time sharing fashion.
- When device wants to transfer the data, he need to wait for it turn. So each devices transfer the data one by one in some particular order defined by the network.

# Network Server

- Network Server became popular in early 1999s as businesses began using PC to provide services hosted on large (powerful) computers.
- Server is a powerful computer that provides various shared resources to the connected client computers.
- Any computer can be a network server in most of the cases. 
- What separates a server from workstation is not the hardware but rather software which is used to perform the specific function on the server depending on the server.
- Here workstation refers to any computer used by individual for his/her day to day task, and network server is any computer that provides the necessary resource on the network.
- Server is a computer program that accepts and responds to request made by other computer known as client.
- Any workstation can be server, but in general server are usually built with more powerful components compared to individual workstation.
  - Generally have more RAM and better Processor.
  - More robust OS and designed to run 24/7

# Types of Network Server

- Web Server
- Email Server
- Application Server
- Database Server
- FTP Server
- Proxy Server
- Streaming Server
- Fax Server
- List Server
- Telnet Server
