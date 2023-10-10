# What Is

- ### What is NaN property in JavaScript ?

NaN property represents the “Not-a-Number” value. It indicates a value that is not a legal number.

> To check if a value is NaN, we use the isNaN() function.

- typeof(NaN) return Number
- isNaN(NaN) return true
- isNaN("Hello") Returns true
- isNaN(undefined) Returns true
- isNaN(345) Returns false
- isNaN(0) Returns false
- isNaN(-5) Returns false
- isNaN('1') Returns false
- isNaN(true) Returns false
- isNaN(false) Returns false

---

- ### What do you mean by strict mode in javascript and characteristics of javascript strict-mode ?

In ECMAScript 5, a new feature called JavaScript Strict Mode allows you to write a code or a function in a "strict" operational environment. In most cases, this language is 'not particularly severe' when it comes to throwing errors. In 'Strict mode,' however, all forms of errors, including silent errors, will be thrown. As a result, debugging becomes a lot simpler. Thus programmer's chances of making an error are lowered.

> Characteristics of strict mode in javascript

1. Duplicate arguments are not allowed by developers.
2. In strict mode, you won't be able to use the JavaScript keyword as a parameter or function name.
3. The 'use strict' keyword is used to define strict mode at the start of the script. Strict mode is supported by all browsers.
4. Engineers will not be allowed to create global variables in 'Strict Mode.

---

- ###
