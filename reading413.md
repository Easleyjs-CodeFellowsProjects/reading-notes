# Reading Notes (401) Reading 13 - easleyjs

Socket.IO

## Questions
**Explain to a non-technical recruiter what the Chat Example (above) does.**

Serves a simple page that allows us to send messages back to the server using socket.io

**What proof of life are we getting on the backend from the above app?**

When a client connects or sends a message, we display a message in the console

**Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?**

socket.broadcast.emit();

**What is a room and how might a room be useful?**

Separate channels within a namespace

**How do you join a room?**

socket.join

**how do you leave a room?**

By disconnecting or the .leave method

**What is a Namespace and what does it allow you to do?**

Allows you to split the logic of your app

**Each namespace potentially has its own what? (hint: 3 things)**

Event handlers, middleware, rooms

**Discuss a possible use case for separate namespaces**

Separate your events out into admin and regular user events
