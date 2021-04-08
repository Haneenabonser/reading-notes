## JavaScript()

**Error Handling & Debugging**     

*execution context*         
In JavaScript, execution context is an abstract concept that holds information about the environment within which the current code is being executed. the JavaScript engine creates the global execution context before it starts to execute any code.                 

*The stack*        
The JS interpreter processes one line of code at a time, when statement need data from another function, it stacks(or piles) the new function on top of the current task. 



*Debugging* : is the process of detecting and removing of existing and potential errors (also called as 'bugs') in a software code that can cause it to behave unexpectedly or crash.

- To deal with Errors, you have to:
     - Debug the code, track down the source of the error,
      and fix it.                              ‏
     - You can handle errors gracefully using try, catch,
       throw, and finally statements.       

- The JavaScript console (one of the programmer tools) will tell us when there is a problem with a script,
where to look for the problem, and what kind of issue it seems to be. 

- JavaScript has 7 different types of errors. Each creates
its own error object, which can tell you its line number
and gives a description of the error.
         - Syntax Error.
         - ReferenceError.
         - EvalError.
         - URI Error.
         - TypeError.
         - RangeError.
         - Error.


- Nan is not an error.
