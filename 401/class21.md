# useState() Hook

## How does React differ from vanilla JS/HTML/CSS?

> Plain JS apps usually start with the initial UI created on the server (as HTML), whereas React apps start with a blank HTML page, and dynamically create the initial state in JavaScript. React requires you to break your UI into components, but plain JS apps can be structured in any way you see fit.

![](https://miro.medium.com/max/957/1*0hgXwcjM-E2wp1NQ3mMOzg.png)

## What is the primary difference between a function component and a class component?

> A functional component is just a plain JavaScript function that accepts props as an argument and returns a React element. A class component requires you to extend from React. Component and create a render function which returns a React element. There is no render method used in functional components.


## React SetState

> React components with state render UI based on that state. When the state of components changes, so does the component UI.

> setState() is the only legitimate way to update state after the initial state setup.

## Handling Events

* React events are named using camelCase, rather than lowercase.

* With JSX you pass a function as the event handler, rather than a string.