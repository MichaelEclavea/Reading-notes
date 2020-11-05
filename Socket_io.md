# Socket.io

1. What is the benefit of transforming data into packets?
- So when data is being sent, the network can spread out data traffic evenly without it getting bogged down all at once. 

2. UDP is often refereed to as a connectionless protocol. Why is this?
- User Datagram Protocol (UDP) is a Transport Layer protocol. UDP is a part of Internet Protocol suite, referred as UDP/IP suite. Unlike TCP, it is unreliable and connectionless protocol. ... User Datagram Protocol (UDP) is more efficient in terms of both latency and bandwidth.[Source](https://www.geeksforgeeks.org/user-datagram-protocol-udp/#:~:text=User%20Datagram%20Protocol%20(UDP)%20is,is%20unreliable%20and%20connectionless%20protocol.&text=User%20Datagram%20Protocol%20(UDP)%20is%20more%20efficient%20in%20terms,of%20both%20latency%20and%20bandwidth.)

3. Can a socket server application have multiple socket connections?
- yes.that is what makes it so powerful and useful. 

4. Can a socket connection application be connected to multiple socket servers?
- no. A socket can only connect to one single port.

5. Can an application be both a socket server and a socket connection?
- Yes. That is what we did in our lab for the past 3 days.

## Vocabulary Terms:

- OSI Model: The OSI Model (Open Systems Interconnection Model) is a conceptual framework used to describe the functions of a networking system. The OSI model characterizes computing functions into a universal set of rules and requirements in order to support interoperability between different products and software.
[Source](https://www.forcepoint.com/cyber-edu/osi-model#:~:text=The%20OSI%20Model%20(Open%20Systems,between%20different%20products%20and%20software.)

- TCP Model: The TCP/IP Reference Model. TCP/IP means Transmission Control Protocol and Internet Protocol. It is the network model used in the current Internet architecture as well. ... These protocols describe the movement of data between the source and destination or the internet. They also offer simple naming and addressing schemes.
[Source](https://www.studytonight.com/computer-networks/tcp-ip-reference-model#:~:text=Key%20Terms-,The%20TCP%2FIP%20Reference%20Model,current%20Internet%20architecture%20as%20well.&text=These%20protocols%20describe%20the%20movement,simple%20naming%20and%20addressing%20schemes.)

- TCP: Transmission Control Protocol (TCP) – a connection-oriented communications protocol that facilitates the exchange of messages between computing devices in a network. It is the most common protocol in networks that use the Internet Protocol (IP); together they are sometimes referred to as TCP/IP. [Source](https://www.sdxcentral.com/resources/glossary/transmission-control-protocol-tcp/#:~:text=Transmission%20Control%20Protocol%20(TCP)%20%E2%80%93,referred%20to%20as%20TCP%2FIP.)

- UDP: User Datagram Protocol (UDP) – a communications protocol that facilitates the exchange of messages between computing devices in a network. It's an alternative to the transmission control protocol (TCP). In a network that uses the Internet Protocol (IP), it is sometimes referred to as UDP/IP. [Source](https://www.sdxcentral.com/resources/glossary/user-datagram-protocol-udp/#:~:text=User%20Datagram%20Protocol%20(UDP)%20%E2%80%93,referred%20to%20as%20UDP%2FIP.)

- Packets: In telecommunications and computer networking, a network packet is a formatted unit of data carried by a packet-switched network. A packet consists of control information and user data; the latter is also known as the payload. Control information provides data for delivering the payload. [Source](https://en.wikipedia.org/wiki/Network_packet)

- Socket: is a software structure within a network node of a computer network that serves as an endpoint for sending and receiving data across the network. The structure and properties of a socket are defined by an application programming interface for the networking architecture. [Source](https://en.wikipedia.org/wiki/Network_socket)