# Event Driven Architecture

## What’s the difference between a FIFO and a standard queue?

> Standard queues guarantee that a message is delivered at least once and duplicates can be introduced into the queue. FIFO queues ensure a message is delivered exactly once and remains available until a consumer processes and deletes it; duplicates are not introduced into the queue.

## How can the server be assured a message was properly received?
> by use expecting to receive an event from the client that the massaged received by it

## What classic design pattern is best represented by event driven programming?

> Event , Singleton

## How do you test an event driven system?

> test event emit and listen it

