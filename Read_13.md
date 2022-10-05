[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 13 - Message Queues

## Discussion Questions

### Socket.io Chat Example

Explain to a non-technical recruiter what the Chat Example (above) does.
> Its a web page that allows a person to enter a message on the page. That message is relayed to our server to be save/processed. In this instance we can just display their message to the web page. Like a simple version of message board or a facebook post.

What proof of life are we getting on the backend from the above app?
> user connected/disconnected

Socket.IO gives us the iO.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?
> The 'broadcast' flag

### Rooms

What is a room and how might a room be useful?
> A concept to subdivide connections into useful 'rooms' to seperate actions from the server. So the server can broadcast messages to some users and not others.

How do you join a room?
> socket.join('room');

how do you leave a room?
> socket.leave('room');

### Namespaces

What is a Namespace and what does it allow you to do?
> A communication channel that allows you to split the logic of your app over a single shared connection.

Each namespace potentially has its own what? (hint: 3 things)
> Event Handlers, Rooms, Middleware

Discuss a possible use case for separate namespaces
> Having an admin namespace that only authorized Admin's can access.

## Things I want to know more about

Definately more about how to properly manage clients moving between namespaces and rooms.

-----
