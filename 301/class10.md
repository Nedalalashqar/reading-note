# In memory storage

## What is a ‘call’?

* The call stack is primarily used for function invocation (call).
* the call stack is synchronous.
* A call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).
* the last function that gets pushed into the stack is the first to be pop out .
* The call stack maintains a record of the position of each stack frame.
* A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.

## What is a ‘refrence error’?

> Types of error messages :

* **Reference errors :**
   1. This happens when trying to reach variables that are not yet declared .
   2. or hoisting let and const that takes time to hoist .
   3. to fix this error declare before initialization .
* Syntax errors :
   1. this occurs when you have something that cannot be parsed in terms of syntax .
   2. Ex : parse an invalid object using JSON.parse.
   3. This can be solved by just fixing the syntax .
* **Range errors :**
   1. manipulate an object with some kind of length and give it an invalid length IS THE CAUSE .
   2. The best approach and best practice is ti immute your variables and don't mess with the lengths .
* **Type errors :**
   1. his types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible .
   2. To fix this make atesting variable or test if the variable or object exists .
* **Debugging : **
   1. To debug your JS code, the easiest and maybe the most common way its to simply console.log() .
   2. by using chrome developer tools .
   3. The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break.
* **Handling errors**
   1. We use try and catch to handle errors .
   2. That will make errors not to break the whole code .
   3. The errors will show in a different way .
* **Tools for preventing runtime Errors :**
   1. quokka to evaluate your code as you type
   2. eslint to make sure your style guide is consistency and it will grab you an error or two along the way and For those of you looking to make JS a more strong typed experience you can check out stuff like TypeScript (like I said in a previous article, when learning I rather avoid libraries that abstract the core language so I wouldn’t recommend this last one when starting).
