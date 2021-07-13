## Message Queues
### Review, Research, and Discussion

- What does it mean that web sockets are bidirectional? Why is this useful?
    - WebSockets allow for full-duplex bidirectional communication. This enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time.
- Does socket.io use HTTP? Why?
    - Socket.io, and WebSockets in general, require an http server for the initial upgrade handshake. So even if you don't supply Socket.io with an http server it will create one for you
- What happens when a client emits an event?
    - Once the browser is connected to the server through websockets, socket.io can send events to the send through the connection. The socket that is passed in the connection event is just a reference to whatever socket gets created when the frontend connects. The socket gets a unique id and with this reference you can communicate in real time to the web browser client.
- What happens when a server emits an event?
    - The event hendler will execute by the the listener.
What happens if a client “misses” an event?
    - The event handler will not run.
How can we mitigate this?
    - By message queues.

### Document the following Vocabulary Terms
- Socket: A socket is one endpoint of a two-way communication link between two programs running on the network.
- Web Socket: is an advanced technology that makes it possible to open a two-way interactive communication session between the user's browser and a server. With this API, you can send messages to a server and receive event-driven responses without having to poll the server for a reply.
- Socket.io: is a library that enables real-time, bidirectional and event-based communication between the browser and the server.
- Client: is a machine or a program that requests for services through the web.
- Server: is a machine or a program that provides services to the clients according to the client's requests.
- OSI Model: (Open Systems Interconnection Model) is a conceptual framework used to describe the functions of a networking system. 
- TCP Model: is a two-layered program: the higher layer (TCP) disassembles message content into small "data packets" that are then transmitted over the Internet to be re-assembled by the receiving computer's TCP back into the message's original form.
- TCP: stands for Transmission Control Protocol a communications standard that enables application programs and computing devices to exchange messages over a network. It is designed to send packets across the internet and ensure the successful delivery of data and messages over networks.
- UDP: User datagram protocol (UDP) operates on top of the Internet Protocol (IP) to transmit datagrams over a network.
- Packets: a packet is a small segment of a larger message. Data sent over computer networks*, such as the Internet, is divided into packets. These packets are then recombined by the computer or device that receives them.

### Preview
- Which 3 things had you heard about previously and now have better clarity on?
    - Events
    - Socket io.
- Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
    - TCP / UDP
What are you most excited about trying to implement or see how it works?
    - Socket chats.

### Preparation Materials
> A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients.

> Each Socket in Socket.IO is identified by a random, unguessable, unique identifier Socket#id. For your convenience, each socket automatically joins a room identified by its own id.

> Socket.IO is composed of two parts:
>   - A server that integrates with (or mounts on) the Node.JS HTTP Server socket.io
>   - A client library that loads on the browser side socket.io-client
