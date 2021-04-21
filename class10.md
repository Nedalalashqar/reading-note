# Error Handling & Debugging

***There are two types of errors in JavaScript :***

* *The first is a programming error* : where we, the JavaScript developers, do something wrong. These types of errors are typically found using our favorite browser and our favorite debugger.
* *The second type of error occurs when the web page reader answers a question incorrectly*

***Order Of Execution***
> To find the source of an error, it helps to know how scripts are processed

***EXECUTION CONTEXT & HOISTING***
> An environment in which the javascript code runs is what form an execution context. and the execution context decides what particular piece of code has access to variables, functions, objects, etc.
*EXECUTION CONTEXT*
> Whenever the code runs for the first time or when the code is not inside any function then it gets into the global execution context. There is only one global execution context throughout the execution of code. In the case of browser global execution context does 2 things :

1. Create a ‘window’ object.

2. The window object is referenced to ‘this’ keyword.

***UNDERSTANDING ERRORS***

> If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code. These errors occur when  engine is parsing a script and encounters syntactically invalid code. If a JavaScript file contains a syntax error, none of the code in the file will execute. Not only will this code produce an error, but the console. log before the invalid syntax won't even run.

***ERROR OBJECTS***

>JavaScript interpreters throw an Error object, when a script error (exception) occurs. In some cases when the error is caused by a DOM operation, JavaScript interpreters throw an DOMException object, not an Error object.

***A DEBUGGING WORKFLOW***

> The process for debugging is different for the two phases of the Data Connector workflow :

* *Debugging the interactive phase* : The interactive phase occurs in the user’s browser, which means that the Javascript surrounding this phase can be debugged using the browser’s developer tools.
* *Debugging the fetch table phase* : The fetch table phase is executed in a NodeJS context within the Intelligence Server (IServer), which means that debugging cannot be handled as normal using the browser’s developer tools and must be handled differently.

> To detect whether the Data Connector's Javascript is being executed within the browser or within the NodeJS context in the IServer, you need to inspect the user agent. If the user-agent contains node.js, you can assume the code is currently being executed within the NodeJS  If you determine that the code is being executed on the browser, simply debug using the browser’s developer tools. However, if the code is being executed on the IServer, you can try one of the methods described below to help debug your fetch table code.
