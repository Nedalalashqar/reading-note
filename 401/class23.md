# Advanced State with Reducers

## How can we ensure that an effect hook runs only once?

> If you want to run an effect and clean it up only once (on mount and unmount), you can pass an empty array ( [] ) as a second argument. This tells React that your effect doesn't depend on any values from props or state, so it never needs to re-run.

## Can useState() update more than one state variable at the same time?

> You could combine the loading state and data state into one state object and then you could do one setState call and there will only be one render. Note: Unlike the setState in class components, the setState returned from useState doesn't merge objects with existing state, it replaces the object entirely.


## Is useState() synchronous?

> useState and setState both are asynchronous. They do not update the state immediately but have queues that are used to update the state object. This is done to improve the performance of the rendering of React components. Even though they are asynchronous, the useState and setState functions do not return promises.