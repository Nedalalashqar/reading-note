# What is a ‘Controlled Component’?

> A **Controlled Component** is one that takes its current value through props and notifies changes through callbacks like onChange . A parent component "controls" it by handling the callback and managing its own state and passing the new values as props to the controlled component

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

> *we wait to store the users responses from the form into state when they submit the form * 
> **because** you need to write an event handler for every way your data can change and pipe all of the input state through a React component. This can become particularly annoying when you are converting a preexisting codebase to React, or integrating a React application with a non-React library.

### How do we target what the user is entering if we have an event handler on an input field?

> by order *event.target.name.*

#### Why would we use a ternary operator?

> Use the ternary operator to simplify your if-else statements that are used to assign values to variables. The ternary operator is commonly used when assigning post data or validating forms.

#### Rewrite the following statement using a ternary statement:

  if(x===y){
 console.log(getFee(true));
  } else {
 console.log(getFee(false));
  }

  