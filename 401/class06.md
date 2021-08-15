## Readings: Authentication

## Explain what a “Singleton” is (in Computer Science terms)

> In software engineering, the singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. The term comes from the mathematical concept of a singleton.
![“inject”](https://opensource.com/sites/default/files/uploads/designpatterns2_singletonpattern.jpg)

## Explain how the Singleton pattern can be used with Node modules, specifically with classes

1. A singleton is a class that allows only a single instance of itself to be created and gives access to that created instance
2. static method would have access to the private constructor.
3. the static method would create an instance of the class if not exists (getInstance()) or call the instance in created before.

## If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?

* Allow the middleware to have access to both layers
* req ,res ,next

## Basic Auth

> basic access authentication is a method for an HTTP user agent (e.g. a web browser) to provide a user name and password when making a request. In basic HTTP authentication, a request contains a header field in the form of Authorization: Basic , where credentials is the Base64 encoding of ID and password joined by a single colon :.

