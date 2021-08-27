# Operators
JavaScript utilizes many types of operators including:
* Assignment
* Comparison
* Arithmetic
* Bitwise
* Logical
* String
* Conditional (ternary)
* Comma
* Unary
* Relational

JavaScript has both **binary** and **unary** operators. It also has one **ternary** operator. 

Binary operators require two operands on either side of the operator. 
> x + y  :: where x & y are operands, and the operator is +.

Unary operators require one operand, which can be placed before or after the operator. 
> x++ :: where x is the operand and ++ is the operator.

Ternary operators take three operands. Only the Conditional Operator requires this one. 
> condition  ? val1 : val2

An extensive list of operators and examples can be found [here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)


# Loops
Loops are tools that repeat a set of instructions.It will continue to repeat until a specified condition is met. 

There are many kinds of loops, but at their core they do the same thing: repeat an action X times. The type of loop helps to determine the start and end points of the loop.  

## For Statement
A `for` loop repeats until a specified condition evaluates to `false`. 

It is used when it is known how many loops it will need to execute. 

Syntax:
`for (statement1; statement2; statement3) {
    //code block to be executed
}`
 
* statement1 is executed once before the execution of the code. 
* statement2 defintes the condition for executing the code block
*statement3 is executed every time the code block has been executed

So in the below example, the code would loop through for every instance where 'x' is less than 10. 

 `for (let i = 1; i < 10; x++) {
     text += "the number is " + i + "<br">;
 }`

## While statement
A `while` statement executes its statements as long as a specified condition evaluaes to `true`. 

While loops are used when the user doesn't necessarily know how long many times the loop will need to run. 

Syntax:

`while (condition)
    //code block to be executed`

So in the below example, this code will run for as long as the variable 'i' is less than 10.

`while (i < 10) {
    text += "The number is " + i;
}`



[Return to Home Page](https://katyroffe.github.io/reading-notes/)