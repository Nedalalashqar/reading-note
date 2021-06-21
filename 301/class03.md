# What does .map() return?

> **map()** function returns a map object(which is an iterator) of the results after applying the given function to each item of a given iterable (list, tuple etc.) ... fun : It is a function to which map passes each element of given iterable. 
> **iter** : It is a iterable which is to be mapped

##  If I want to loop through an array and display each value in JSX, how do I do that in React?

1. ***Using For Loop***
> It requires you to iterate through the array and push the elements into a new array and then wrap the array by curly brace inside the return statement.

2. ***Using Array.map() method***
> The most commonly used method for iterating through an array in React.js. It prevents you from declaring a new array. Array.map() method returns a new array of the jsx elements.

### Each list item needs a unique ____ .

> This is because React needs to uniquely identify each items in the list

#### What is the purpose of a key?

>A “key” is a special string attribute you need to include when creating lists of elements in React. Keys are used to React to identify which items in the list are changed, updated, or deleted. In other words, we can say that keys are used to give an identity to the elements in the lists

##### What is the spread operator?

> The Spread operator lets you expand an iterable like an object, string, or array into its elements while the Rest operator does the inverse by reducing a set of elements into one array

###### List 4 things that the spread operator can do.
* *Function arguments/calls*
*  *Array*
* *Object*
* *React Props*

###### Give an example of using the spread operator to combine two arrays.

![example](https://miro.medium.com/max/3208/1*ck6Fs5k54T8Yv09D2dS0jA.png)