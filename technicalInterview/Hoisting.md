# Hoisting in javascript

> _Hoisting work with (var) & function(), and doesn't work with (let or const) and arrow function_

- ### Explain Hoisting in javascript ?

Hoisting is the default behaviour of javascript where all the variable and function declarations are moved on top.

**Example 1:**

hoistedVariable = 3;

console.log(hoistedVariable); // outputs 3 even when the variable is declared after it is initialized

var hoistedVariable;

---

**Example 2:**

hoistedFunction();  
// Outputs " Hello world! " even when the function is declared after calling

function hoistedFunction(){

console.log(" Hello world! ");

}

- ### difference between the hoisting behavior with var and let/const ?

Variables declared with let or const are hoisted WITHOUT a default initialization.

But variables declared with var are hoisted WITH a default initialization of undefined.

---

### References

- [freecodecamp](https://www.freecodecamp.org/news/javascript-let-and-const-hoisting/)

- [interviewbit](https://www.interviewbit.com/javascript-interview-questions/#different-data-types-present-in-javascript)
