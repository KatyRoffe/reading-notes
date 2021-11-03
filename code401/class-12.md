# Socket.io

1. What is the benefit of transforming data into packets?

- the data is split into smaller pieces for easier management

2. UDP is often refereed to as a connectionless protocol. Why is this?

- UDP needs no connection to be established between the source and destination before transmitting data, and does not have a mechanism in place to ensure the payload isn't corrupted

3. Can a socket server application have multiple socket connections?

- yes, but each socket listening to the same port must be associated with a different IP adress

4. Can a socket connection application be connected to multiple socket servers?

- yes

5. Can an application be both a socket server and a socket connection?

- yes

## Vocab

- **Observer Pattern:** a pattern where an object (subject) has a lsit of dependents (obserers) and notifies them of state changes
- **Listener:** a function that waits for an event to occur
- **Event Handler:** callback function for when an event is triggered
- **Event Driven Programming:** the flow of the program is determined by events
- **Event Loop:** waits for events to occur
- **Event Queue:** holds events for processing
- **Call Stack:** mechanism to keep track of the current place in the script
- **Emit/Raise/Trigger:** begins an event
- **Subscribe:** listening for events 
- **database:** organized storage for data

### Materials
- [Socket.io Docs](https://socket.io/docs/)
- [Socket.io Server API](https://socket.io/docs/server-api)
- [Socket.io Client API](https://socket.io/docs/client-api)
- [Socet Testing Tool](https://amritb.github.io/socketio-client-tool/)
- [Web sockets](https://en.wikipedia.org/wiki/WebSocket)
- [Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)
- [Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)
- [OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)
- [TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)
