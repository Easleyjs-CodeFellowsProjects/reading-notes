# Reading Notes (401) Reading 12 - easleyjs

WebSockets and Socket.IO

## Questions
**What is a Web Socket?**

A protocol that allows full-duplex communication between a server and a client.

**Describe the Web Socket request/response handshake and what happens once the connection is established.**

The client sends a WebSocket handshake request, and the server returns a WebSocket handshake response. After it's accepted, they switch over to the WebSocket protocol.

**Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.**

Request

**What does the event handler io.on() do?**

Sets up a socket

**Describe some possible proof of life or proof that the code works as expected**

io.on('connection', function(socket){
   console.log('A user connected');

If we make a connection to this server, on the server we should see the console.log

**What does socket.emit() do?**

Sends out an event on that socket

**What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0)**

WebSockets are the technology, Socket.IO is a library that makes it easier to use that technology in your app.

**When would you use Socket.IO?**

If you need some it's features like broadcasting, or fall-back to non-websocket technologies.

**When would you use WebSockets?**

If you can't use Socket.IO, or specifically need to use it for TCP purposes.

**OSI Model - What are a couple of key takeaways from this video?**

Almost all of the work we do is in the Application layer (HTML, JS). The OSI model is like a Russian nesting doll where the packet with the application data is nested in the other layers for transport.

**Explain TCP Handshakes**

Before two computers can communicate, the client sends a message labeled "SYN" - synchronization, requesting a connection. The second computer send a "SYN-ACK" acknowledgement. The client then accepts the connection and it's established from there.
