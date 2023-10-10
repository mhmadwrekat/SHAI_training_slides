# Differences

- ### Difference between “ == “ and “ === “ operators ?

Both are comparison operators. The difference between both the operators is that “==” is **used to compare values** whereas, “ === “ is **used to compare both values and types.**

> Example

var x = 2;

var y = "2";

> (x == y) // Returns true since the value of both x and y is the same
> (x === y) // Returns false since the typeof x is "number" and typeof y is "string"

---

- ### Difference between var and let keyword in javascript ?

Some differences are

1. The keyword 'let' was just added in 2015.

2. The keyword 'Var' has a function scope. Anywhere in the function, the variable specified using var is accessible but in ‘let’ the scope of a variable declared with the 'let' keyword is limited to the block in which it is declared. Let's start with a Block Scope.

---





