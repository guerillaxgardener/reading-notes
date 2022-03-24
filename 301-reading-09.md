# Code 301 Reading 9: Functional Programming

## [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

* What is functional programming?

  * this is a style for building our programs that avoids changing state and mutable data and treats computation as evaluation of a math function.

* What is a pure function and how do we know if 
something is a pure function?

  * A pure function should not cause any side effects and should always return the same result with the same arguments

  * If a function reads external files, it's impure.

* What are the benefits of a pure function?

  * They will not affect other parts of application we are not intending.

  * "pure functions are stable, consistent, and predictable."

* What is immutability?

  * something is immutable when it's value of state cannot be changed after creation

* What is Referential transparency?

  * when we have a function that will yield the same results for same input we call it referential transparency.

---

## [Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)

* What is a module?

  * An individual JavaScript file that is a logical division of a specific functionality within application we're building.

* What does the word ‘require’ do?

  * requires a different module js file within the file we've included it in

  * looks into required component, finds it, and returns whatever is exported.

* How do we bring another module into the file the we are working in?

  * module.export whatever we want available from component we're importing

  * require that component in the file we're working in. and whatever is being exported is returned to us.

* What do we have to do to make a module available?

  1. Create the module

  2. Encode the functionality we want in this module

  3. module.export withing that component whatever we would like to return and use elsewhere

  4. require that module in whatever component or file withing application that you want to pull in the exported functionality within.


---

<===== [BACK!](README.md)
