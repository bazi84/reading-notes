# The typles of operator Javascript has

Assignment operators
Comparison operators
Arithmetic operators
Bitwise operators
Logical operators
String operators
Conditional (ternary) operator
Comma operator
Unary operators
Relational operators

JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator.

A binary operator requires two operands, one before the operator and one after the operator:
For example, 3+4 or x*y.

A unary operator requires a single operand, either before or after the operator:

An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x.

# Functions

A JavaScript function is a block of code designed to perform a particular task.

## *You can reuse code: Define the code once, and use it many times.*

You can use the same code many times with different arguments, to produce different results.

A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:

The name of the function.
A list of parameters to the function, enclosed in parentheses and separated by commas.
The JavaScript statements that define the function, enclosed in curly brackets, {...}.

function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
}


## JavaScript Function Syntax

function name(parameter1, parameter2, parameter3) {
  // code to be executed
}

## Function Return

let x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}

# Control Flow

The control flow is the order in which the computer executes statements in a script.

## A conditional structure
if (field==empty) {
    promptUser();
} else {
    submitForm();
}
