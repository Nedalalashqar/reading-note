# APIs

## What does REST stand for?

> REST APIs are:
* Designed around resources
* Driven by hypermedia links
* Use a stateless request model

## REST APIs are designed around a ____.

> REST APIs are designed around resources .

## What is an identifer of a resource?

> * An identifier is unique to the resource. For example, an isbn number for a resource like a book.

## What are the most common HTTP verbs?

> **HTTP verbs:** GET, POST, PUT, PATCH, DELETE These are standard and included in the uniform interface for REST APIs that are built using HTTP.

## What should the URIs be based on?

> **URIs** should be based on nouns and NOT verbs. Meaning, something like https://github.com/profile is better than https://github.com/edit-profile

## Give an example of a good URI.

> A good **URI** also doesn't have the exact same wording as what is going on internally in the program- it is good to make the client unaware of that terminology
> It is also good form to have a naming convention for URI.

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

> A ‘chatty’ web API? means that the API is sending a bunch of requests for individual or small chunks of data. It is better to request this data is fewer requests.

## What status code does a successful GET request return?

> Get gets the representation of a resource at the URI

## What status code does a successful POST request return?

> Post creates new resource at URI, or can trigger operations that don't create resources

## What status code does a successful DELETE request return?

> Delete removes resource at URI

* a successful GET request returns --> 202 (OK)

* an unsuccessful GET request returns --> 404 (Not Found)

*  a successful POST or PUT request returns --> 201 (Created)

* a successful DELETE request returns --> 204

