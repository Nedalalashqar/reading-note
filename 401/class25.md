# Context API

## Describe use cases useState() vs useReducer()

![token](https://res.cloudinary.com/practicaldev/image/fetch/s--1ICd6TAL--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/k0z9r0fyhojaytokogf2.JPG)

## Why do custom hooks need the use prefix?

> This is mainly to have an extra option for sharing state and logic between components. ... Custom hooks are normal JS functions, named with the prefix 'use'
## What do custom hooks usually do?

> that can use hooks inside of it and contain a common stateful logic to be reused in other components.

## Using any list of custom hooks, research and name one that you think will be useful in your applications

> Custom React Hooks allow us to extract component logic into reusable functions. Custom Hooks look very much like normal helper functions, except they can maintain component state and perform effects. So if you find yourself using a lot of these Hooks, you might as well import the package.

## Describe how a hook that fetches API data might work

> hook might take in a url, a method, and a body. Using axios or something similar, useState and possibly useEffect, an API call can be made based on and using the parameters passed in and then an objects state could be ‘set’ based on the results of the API call

> reducer => NgRx are responsible for handling transitions from one state to the next state in your application. Reducer functions handle these transitions by determining which actions to handle based on the action's type