# Problem Domain, Objects, and the DOM

**What is an Object ?**

* Objects are key to understanding object-oriented technology. Look around right now and you'll find many examples of real-world objects: your dog, your desk, your television set, your bicycle.
* Real-world objects share two characteristics: They all have state and behavior. Dogs have state (name, color, breed, hungry) and behavior (barking, fetching, wagging tail). Bicycles also have state (current gear, current pedal cadence, current speed) and behavior (changing gear, changing pedal cadence, applying brakes). Identifying the state and behavior for real-world objects is a great way to begin thinking in terms of object-oriented programming.

## Document Object model

> The Document Object Model is a programming API for documents. The object model itself closely resembles the structure of the documents it models
> The Document Object Model represents this table like this:
![Document Object model](https://www.w3.org/TR/WD-DOM/table.gif)
> The name "Document Object Model" was chosen because it is an "object model" is used in the traditional object oriented design sense: documents are modeled using objects, and the model encompasses not only the structure of a document, but also the behavior of a document and the objects of which it is composed. In other words, the nodes in the above diagram do not represent a data structure, they represent objects, which have functions and identity. As an object model, the Document Object Model identifies:

* the interfaces and objects used to represent and manipulate a document
* the semantics of these interfaces and objects - including both behavior and attributes
* the relationships and collaborations among these interfaces and object

### Understanding The Problem Domain Is The Hardest Part Of Programming

***Why problem domains are hard ?**
> Have you ever tried to put together a jigsaw puzzle that didn’t have any picture on it?  How about one like this one, that has a very similar pattern repeated on it and is double-sided?
>The reason why puzzles like this one are so hard, is because you can’t really see what you are trying to build very clearly.  Normally when you put together a jigsaw puzzle you follow steps that might look something like this:

1. Figure out what the major components of the picture are
2. Sort the pieces by color or component
3. Put together all the border pieces
4. Put together each component of the picture from the piles you created

> This all breaks down when you don’t have a picture with clear components that you can identify.
> The same thing happens when writing code.  Writing code is a lot like putting together a jigsaw puzzle.  We put together code with the purpose of building components that we have taken out of the “bigger picture” of the problem domain.
> As programmers, we also are often not given complete information about the problem domain, so we don’t even have the information we need to understand it.
> Just try and read the famous Domain Driven Design book and you’ll quickly see how complicated and difficult problem domains can be.  (Great book by the way, although you may have to read it twice or three times—I certainly did.)
