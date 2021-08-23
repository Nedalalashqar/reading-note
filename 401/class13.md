# Message Queues

## What does it mean that web sockets are bidirectional? Why is this useful?

> It means that the data flows in both ways (full-duplex), a web socket can both send and receive which is useful because it allows data to be sent and received on the same channel.

## Does socket.io use HTTP? Why?

> Yes, it use HTTP. Socket.io will try to establish a WebSocket if possible but if it cannot it will fall back on HTTP.

## What happens when a client emits an event?

> Whenever server is emitting an event it will be send to all client’s socket connected and listen to it.

## What happens when a server emits an event?

> The socket that miss an event won’t recognize it later and it will be ignored.

## How can we mitigate this?

> To avoid missing an event by caching the events on the server and when the client recive the event it will emit an event to the server, so that the server will awknowladge the client got the message and the server will remove the event from the chach. And every time the client start a connection with the server he will emit an event to get the events that he missed.

