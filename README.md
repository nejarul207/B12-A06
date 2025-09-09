1. Difference between var, let, and const:

var- function-scoped, can be redeclared, hoisted.

let - block-scoped, cannot be redeclared in same scope, not hoisted like var.

const - block-scoped, cannot be reassigned, must be initialized.


2. Difference between map(), forEach(), and filter():

forEach() - executes a function for each array element, returns undefined.

map() - executes a function for each element and returns a new array.

filter() - returns a new array with elements that pass a test.


3. Arrow Functions in ES6:
Arrow functions provide a shorter syntax for writing functions using =>. They have lexical this (use surrounding context), implicit return for single expressions, and cannot be used as constructors.


4. Destructuring assignment work in ES6:
    Destructuring allows unpacking values from arrays or properties from objects into distinct variables in a concise syntax.



5. Explain template literals in ES6. How are they different from string concatenat?
   
Template Literals in ES6:
Template literals use backticks (`) to create strings and allow embedded expressions with ${}. They support multiline strings easily.

Difference from string concatenation:
Template literals are cleaner and easier for embedding variables and expressions.
Concatenation uses + and is less readable: "Hello, " + name + "!".
