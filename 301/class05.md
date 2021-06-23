# How would you break a mock into a component heirarchy?

> Draw boxes around each wonder (and child component) in the model and give them all the names. But how do you know what should be its component? Use the same techniques to decide whether to create a new function or object. One of these approaches is the single responsibility principle, that is, the component should ideally do one thing. If it ends up growing, it should break down into smaller subcomponents.

## What is the single responsibility principle and how does it apply to components?

> **The single-responsibility principle (SRP)** is a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part.

## What does it mean to build a ‘static’ version of your application?

* *In a statically built program*, no dynamic linking occurs: all the bindings have been done at compile time. ... As a result, when installing a statically-built program on a computer, the user doesn't have to download and install additional libraries: the program is ready to run.

## Once you have a static application, what do you need to add?

> You will have a public library, public gallery, your own photo model. Still under construction. Pictures as an item. If you change the base data model and call ReactDOM.render() again, the UI will be refreshed. You can see how to update your user interface and where to make changes. Uniform data maintains in React (also called unary binding renders) making it all modular and fast.

## What are the three questions you can ask to determine if something is state?

1. **Is it passed in from a parent via props?**
2.  **Does it remain unchanged over time?**
3. **Can you compute it based on any other state or props in your component?**

## How can you identify where state needs to live?

* Select each component that displays something based on that state. Find a common owner component (one component above all components that need state in the hierarchy).
* It must be owned by either the co-owner or another higher element in the state hierarchy.

> If you can't find a component where it makes sense to own the state, create a new one to keep the state only and add it somewhere in the hierarchy above the co-owner component.