# In memory storage

### What is a ‘call’?
Function invocation

### How many ‘calls’ can happen at once?
one

### What does LIFO mean?
Last one First Out

### Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
```
function firstFunction(){
  console.log("Hello from firstFunction");
}

function secondFunction(){
  firstFunction();
  console.log("The end from secondFunction");
}

secondFunction();

```

### What causes a Stack Overflow?
 when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.
 
 
 
# JavaScript error messages 

### What is a ‘reference error? 
The ReferenceError object represents an error when a variable that doesn't exist (or hasn't yet been initialized) in the current scope is referenced.

### What is a ‘syntax error? 
is an error in the syntax of a coding or programming language

### What is a ‘range error’? 
A RangeError is thrown when trying to pass a value as an argument to a function that does not allow a range that includes the value. This can be encountered when: passing a value that is not one of the allowed string values to String

### What is a ‘tyep error’? 
The TypeError object represents an error when an operation could not be performed, typically (but not exclusively) when a value is not of the expected type. A TypeError may be thrown when: an operand or argument passed to a function is incompatible with the type expected by that operator or function; or.

### What is a breakpoint? 
In the debugger window, you can set breakpoints in the JavaScript code. At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values. After examining values, you can resume the execution of code (typically with a play button).

### What does the word ‘debugger’ do in your code? 
A debugger is a software tool that can help the software development process by identifying coding errors at various stages of the operating system or application development. Some debuggers will analyze a test run to see what lines of code were not executed.



