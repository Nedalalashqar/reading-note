# < Login /> and < Auth />

## Why is the Context API useful?

> The Context API is a React structure that enables you to exchange unique details and assists in solving prop-drilling from all levels of your application.

## Can a component outside of a provider get its context?

> To access a React context outside of the render function, we can use the useContext hook. We create the UserContext by calling the React. createContext method with a default context value. Then in the Users component, we call the useContext hook with UserContext to accxess the current value of UserContext

## What are some common use cases for using the Context API?

> Context is primarily used when some data needs to be accessible by many components at different nesting levels. Apply it sparingly because it makes component reuse more difficult. If you only want to avoid passing some props through many levels, component composition is often a simpler solution than context.

## Describe “Context Hell”

> the React Context hell is the nasty code you get taking advantage of the React Context API
