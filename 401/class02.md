# Review, Research, and Discussion

## What’s the difference between PUT and PATCH?

* The main difference between PUT and PATCH requests are in the way the server processes the enclosed entity to modify the resource identified by the Request-URI.

* In a PUT request, the enclosed entity is considered to be a modified version of the resource stored on the origin server, and the client is requesting that the stored version be replaced.

* With PATCH, however, the enclosed entity contains a set of instructions describing how a resource currently residing on the origin server should be modified to produce a new version.

* Also, another difference is that when you want to update a resource with PUT request, you have to send the full payload as the request whereas with PATCH, you only send the parameters which you want to update.

## Provide links to 3 services or tools that allow you to “mock” an API for development like json-server

1. **MockServer**
MockServer (and its counterpart service MockServer Proxy) is a multifaceted tool that comes in a variety of builds. It’s available as a Netty web server, a Docker container, a Maven plugin, an npm plugin, and a Grunt plugin. There’s a ton of great options that can be leveraged for a variety of environments. This already makes it a pretty compelling tool given that you can plug it into just about anything you’re running, but its wide range of functionality is the core compelling argument.
> link : [MockServer](https://www.mock-server.com/).

2. **Mockoon**
Mockoon departs from the other solutions on this list in that it’s neither a web solution nor a code solution. Mockoon is a downloadable program that mocks an unlimited number of environments and routes – Mockoon makes a point to note that these can be run in parallel, and its strong import/export system ensures that enterprise, multi-path, multi-environment situations can be adequately supported.
> link : [Mockoon](https://mockoon.com/).

3. **Mocky.io**
Mocky is an incredibly simple and super lightweight testing implementation. Mocky is entirely a web app, meaning that everything is generated and managed remotely. This does mean that Mocky grants you significantly less control compared to solutions that focus more on local systems, but this also means the application is simpler and cleaner.
> link : [Mocky.io](https://designer.mocky.io/).

## Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?

> Swagger status Codes:
* **200** : Successful request and response.
* **400** : Bad request
* **404** : Not found
* **500** : Unexpected error
> APIDoc.js HTTP status Codes:
* **200** : Successful request and response.
* **400** : Bad request
* **404** : Not found
* **500** : Unexpected error

## Compare and contrast SOAP and ReST
> ReST 
1. REST is all about simplicity, thanks to HTTP protocols.
2. REST APIs facilitate client-server communications and architectures. If it’s RESTful, it’s built on this client-server principle, with round trips between the two passing payloads of information.
3. REST APIs use a single uniform interface. This simplifies how applications interact with the API by requiring they all interface in the same way, through the same portal. This has advantages and disadvantages; check with your developer to see if this will affect implementation changes down the road.

> SOAP
1. SOAP has tighter security. WS-Security, in addition to SSL support, is a built-in standard that gives SOAP some more enterprise-level security features, if you have a requirement for them.
2. Successful/retry logic for reliable messaging functionality. Rest doesn’t have a standard messaging system and can only address communication failures by retrying. SOAP has successful/retry logic built in and provides end-to-end reliability even through SOAP intermediaries.
3. SOAP has built-in ACID compliance. ACID compliance reduces anomalies and protects the integrity of a database by prescribing exactly how transactions can interact with the database. ACID is more conservative than other data consistency models, which is why it’s typically favored when handling financial or otherwise sensitive transactions.




