[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 12 - Socket.IO

## Discussion Questions

### Web Sockets

What is a Web Socket?
>A communications protocol. Websockets (plural) is the current API standard to use this protocol. 

Describe the Web Socket request/response handshake and what happens once the connection is established.
> Client sends a Web Socket handshake request. Server sends a Web Socket handshake response. Than handshake uses HTTP request/response, then once a connection is established it switches to a bidirectional binary protocol.

Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.
> request

### Socket.io Tutorial

What does the event handler io.on() do?
> The io.on event handler handles connection, disconnection, etc., events in it, using the socket object.

Describe some possible proof of life or proof that the code works as expected
> Could setup the server to log connections/disconnects of the socket.io.

What does socket.emit() do?
>You can create and fire custom events using the socket.emit function.

### Socket.io vs Web Sockets

What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).
> Websocket is the protocol which handles the communication, Socket.IO is the library to work with Websocket and provides event based communication between browser and server.

When would you use Socket.IO?
> Provides event based communication between browser and server. Can support proxies and load balancers. Supports broadcasting and fallback options. When these are the priorities you would use Socket.IO.

When would you use WebSockets?
> Provides full-duplex communication on TCP connections. Provides an accurate and efficient event transfer with low latency. Removes overhead and reduces complexity. When these are priorites you would use Websockets.

### OSI Model Explained

What are a couple of key takeaways from this video?
> Open System Integration Model (OSI). 7 layers. Session layer handles Authorization and Authentication. Transport Layer has TCP(feedback) and UDP(no feedback).

### TCP Handshakes Explained

Translate the gist of this video to a non-technical friend
> The 3-way TCP handshake is like a neighbor from a sitcom.
>
> 1) Neighbor, knocks on door, "hello pal you home?"
> 2) HomeOwner, "Howdy Neighbor, doors open!" 
> 3) Neighbor, "Okay, thanks, I brought a pie over."
>
> The two acknowledge each other and then the delivery of data(pie) can happen.

## Things I want to know more about

We did a basic version of event driven setup today. Will socket.io make it easier to manage all the events and their listeners. 

-----
