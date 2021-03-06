# Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
> componentDidMount

## What is the very first thing to happen in the lifecycle of React?

* **Mounting**
> When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.

### Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

* **constructor** 
> The constructor for a React component is called before it is mounted.If the component is a subclass you should call super(props), or the props will be undefined. constructors can be used to assign state using this.state or to bind event handle methods to an instance. Let’s take a look at some example code.

* **render**
> Render is the only required method in a class component. It will examine this.props and this.state when called. The render function should not modify the component state because it would cause a lot of bugs by changing the state every time it rerenders. I also should not directly interact with the browser. render will not be invoked if shouldComponentUpdate() returns false. Here is an example of using render.

* **componentDidMount** 
> This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().

* **React Updates** 
> The default behavior in react is to rerender after every state change. Setting shouldComponentUpdate() to false allows you to prevent this from happening. This is in order to optimize performance. If you want to use this method, it may be better to use PureComponent instead, which performs a shallow comparison of props and state. If you do decide to use this method, be sure to check the previous props and state with the current props and state. If shouldComponentUpdate() returns false, then UNSAFE_componentWillUpdate(), render(), and componentDidUpdate() will not be invoked.

* **componentWillUnmount**
>This method allows you to clean up the DOM and netwrok requests/ subscriptions.


#### What types of things can you pass in the props?
> Props (aka "properties") in React allows us to pass values from a parent component down to a child component. The values can be any data type, from strings to functions, objects, etc

##### What is the big difference between props and state?
> Basically, the difference is that state is something like attributes in OOP : it's something local to a class (component), used to better describe it. Props are like parameters - they are passed to a component from the caller of a component (the parent) : as if you called a function with certain parameters

###### When do we re-render our application?
> React components automatically re-render whenever there is a change in their state or props. A simple update of the state, from anywhere in the code, causes all the User Interface (UI) elements to be re-rendered automatically

###### What are some examples of things that we could store in state?
>  example of UI data that you could store in local state would be the currently selected tab from a list of options.

