# Readings: Express REST API


## Name 3 real world use cases where you’d want to change the request with custom middleware

* Middleware has access to request and response object

* Middleware has access to next function of request-response life cycle

* Call the next middleware in the stack.

## True or false: The route handler is middleware?

> **True**

## In what ways can a middleware function end the process and send data to the browser?

> If the current middleware function does not end the request-response cycle, it must call next() to pass control to the next middleware function. Otherwise, the request will be left hanging.

## At what point in the request lifecycle can you “inject” middleware?

>  Just as with providers and controllers, they are able to inject dependencies that are available within the same module. As usual, this is done through the constructor.

![“inject”](https://loopback.io/pages/en/lb4/imgs/middleware-classes.png)

## What can cause express to error with “Request headers sent twice, cannot start a second response”

> Doesn't send anything