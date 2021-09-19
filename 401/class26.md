# Context API - Behaviors

## When you have multiple contexts, what component type should you use (class/function) and why?

> In class components, the render method will be called, whenever the state of the components changes. On the other hand, the Functional components render the UI based on the props. Class Components should be preferred whenever we have the requirement with the state of the component

![token](https://miro.medium.com/max/1838/1*HCUtuON8qsHAyWusOsR64A.png)

## What are some good use cases for using the Context API for global state?

> From React’s own docs they say that Context provides a way to pass data through the component tree without having to pass props down manually at every level

## How can you best test context?

> **context=>** method to pass props from parent to child component(s), by storing the props in a store(similar in Redux) and using these props from the store by child component(s) without actually passing them manually at each level of the component tree

> **useContext()=>** create common data that can be accessed throughout the component hierarchy without passing the props down manually to each level

> **static context=>** which wraps our component with PureComponent shallow comparison logic while also allowing us to pass references from our context
