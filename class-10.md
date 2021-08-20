# JS Reading

## Ch. 10: “Error Handling & Debugging”

- JavaScript is a puzzle. Not only do we have to put the puzzle together, but we have to make it possible for the computer to read it as well. 
- nobody codes correctly their first time
- Learn to understand exeecution contexts to make it easier to the error in the code
- finding errors  = **debugging**, often a process of deduction
- console helps narrow down the area where the errors are located
- there are 7 types of errors
    - Error :: general error
    - Syntax Error :: syntax has not been followed
    - ReferenceError :: Tried to reference a variable not declared or within scope
    - TypeError :: unexpected data type
    - RangeError :: numbers not in an acceptable range
    - URIError :: encodeURI()/decodeURI() and similar others used incorrectly
    - EvalError :: eval() used incorrectly
- When an error object is created, it will contain certain properties
    - name :: type of error
    - message :: description of the error
    - fileNumber :: name of the JS file
    - lineNumber :: line number of error
- Most browsers have some form of a developer tool available to help with debugging
- Handle gracefully :: use try, catch, throw, and finally statements