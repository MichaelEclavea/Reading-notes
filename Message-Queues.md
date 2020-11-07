# Message Queues

1. What does it mean that web sockets are bidirectional? Why is this useful?
- This means that communication can be sent from server to client and client to server. 
(Both directions). 

2. Does socket.io use HTTP? Why?
- Yes. The initial connection is done over HTTP. 

3. What happens when a client emits an event?
- When the client emits an event, this essentially means they are sending data. 

4. What happens when a server emits an event?
- When the server emits an event, the client listening on the other end with the same .on method, will receive the data being sent by the server. 

5. What happens if a client “misses” an event?
- Not certain, but i am thinking that it is sent into a queue it might sit until the client finally makes the connection to the server then receive it then> 

6. How can we mitigate this?
- Idk.

## Vocabulary Terms

- Web Socket:  is an advanced technology that makes it possible to open a two-way interactive communication session between the user's browser and a server. With this API, you can send messages to a server and receive event-driven responses without having to poll the server for a reply.
[Source](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API#:~:text=The%20WebSocket%20API%20is%20an,the%20server%20for%20a%20reply.)

- Socket.io: Socket.IO enables real-time, bidirectional and event-based communication.
It works on every platform, browser or device, focusing equally on reliability and speed.[Source](https://socket.io/)

- Client: is a computer or a program that, as part of its operation, relies on sending a request to another program or a computer hardware or software that accesses a service made available by a server (which may or may not be located on another computer). [Source](https://en.wikipedia.org/wiki/Client_(computing)#:~:text=A%20client%20is%20a%20computer,be%20located%20on%20another%20computer).)

- Server:  is a piece of computer hardware or software (computer program) that provides functionality for other programs or devices, called "clients". This architecture is called the client–server model. [Source](https://en.wikipedia.org/wiki/Server_(computing)#:~:text=In%20computing%2C%20a%20server%20is,called%20the%20client%E2%80%93server%20model.)