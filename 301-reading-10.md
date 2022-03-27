# Code 301 Reading 10 In Memory Storage

## [Understanding the JavaScript Call Stack](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)

What is a ‘call’?

* A 'call' is a function invocation

How many ‘calls’ can happen at once?

* One at a time

What does LIFO mean?

* last in, first out; this means that the last thing to be added into some set of data will also be the first thing removed

Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

![call stack and functions involved](./img/call-stack%20.jpeg "call stack")


What causes a Stack Overflow?

* a function calls itself without an endpoint (recursive)

---
---

## [JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

What is a ‘refrence error’?

* a declaration is made on a variable that does not exist or in the case of `let` and `const` the variable may exist, but be in hoisting limbo known as a 'temporary dead zone'

What is a ‘syntax error’?

* something is put together incorrectly creating an issue when code is parsed.

What is a ‘range error’?

* Utilizing length in your code and giving reference to an invalid length, like a negative array index.

What is a ‘type error’?

* This occurs when data types are being used in ways that are incompatible with each other.

What is a breakpoint?

* debugging tool inserted to stop at lines of code if a condition is met

What does the word ‘debugger’ do in your code?

* adding 'debugger' into your code inserts a breakpoint.

---

<===== [BACK!](README.md)
