## In memory storage

**Understanding the JavaScript Call Stack**
- What is a ‘call’?
    - Is primarily used for function invocation, is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).
- How many ‘calls’ can happen at once?
    - Infinitely, Not really until we don't overflow the stack with function calls. Since each time a function is called all the variables used need space to be store in stack and stack is of limited size.
- What does LIFO mean?
    - When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns
- What causes a Stack Overflow?
    - Infinite recursion, in which a function calls itself so many times that the space needed to store the variables and information associated with each call is more than can fit on the stack.


**JavaScript error messages**
- What is a ‘refrence error’?
    - When any value is assigned to undeclared variable or assignment without the var keyword or variable is not in your current scope.
- What is a ‘syntax error’?
    - Syntax errors are mistakes in using the language like missing a comma or a quotation mark, or misspelling a word.
- What is a ‘range error’?
    - Is thrown when trying to pass a number as an argument to a function that does not allow a range that includes that number. 
- What is a ‘tyep error’?
    - May be thrown when: an operand or argument passed to a function is incompatible with the type expected by that operator or function.
- What is a breakpoint?
    - Is a point in the program where the code will stop executing.
- What does the word ‘debugger’ do in your code?
    - Is the process of detecting and removing of existing and potential errors (also called as 'bugs') in a software code that can cause it to behave unexpectedly or crash.


 ## Things I want to know more about
