# In memory storage

## [Understanding the JavaScript Call Stack](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)

- What is a ‘call’?
  - invoking a function

- How many ‘calls’ can happen at once?
  - functions are executed one at a time (from top to bottom) / synchronous

- What does LIFO mean?
  - last in, first out

- Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

>function theFirst(){
>  console.log("Once upon a time");
>}
>
>function theSecond(){
>  theFirst();
>  console.log("And they lived happily ever after");
>}
>
>theSecond();

- What causes a Stack Overflow?
  - when a function calls itself and has no exit point 

## [JavaScript Error Messages & Debugging](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

- What is a ‘refrence error’?
  - when something is used without being declred (it's undefined)

- What is a ‘syntax error’?
  - when something can't be parsed due to issues in the syntax

- What is a ‘range error’?
  - when a range is invalid (isn't possible or doesn't exist, like a negative position in an array)

- What is a ‘type error’?
  - when the type is incomatible or undefined

- What is a breakpoint?
  - a place where you tell the code to stop so you can inspect what's happening

- What does the word ‘debugger’ do in your code?
  - it's a way to create a breakpoint

## Additional Resources
- [JavaScript errors reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)

## Things I want to know more about