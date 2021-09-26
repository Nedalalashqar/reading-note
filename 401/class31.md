#  Redux - Combined Reducers

## Why choose Redux instead of the Context API for global state?

> context API is easy to is use as it has a short learning curve. It requires less code, and because there’s no need of extra libraries, bundle sizes are reduced. Redux on the other hand requires adding more libraries to the application bundle. The syntax is complex and extensive creating unnecessary work and complexity

## What is the purpose of a reducer?

> takes the previous state and an action, and returns the next state

## What does an action contain?

> In Redux, a reducer is a pure function that takes an action and the previous state of the application and returns the new state. The action describes what happened and it is the reducer’s job to return the new state based on that action

## Why do we need to copy the state in a reducer?

> change values inside an object and we want to know if something has changed, we'd have to make a full copy so we can store individual properties, and then compare each property of the new and old object to determine what, if anything, has change.
