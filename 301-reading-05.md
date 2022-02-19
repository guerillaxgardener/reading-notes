# Code 301 Reading 5: Putting it all together

## [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

___What is the single responsibility principle and how does it apply to components?___

*  Single responsibilty princple is the belief within programming that says "modules, classes, and functions within a cpomputer program should only have responsibility over a [single part of programs functionality"](https://en.wikipedia.org/wiki/Single-responsibility_principle) <br> -wikipedia

___What does it mean to build a ‘static’ version of your application?___

* This is the initial version of our App that wll render UI but without interactivity.

  * static building: much type, little think

  * interactivity build: much think, little type

___Once you have a static application, what do you need to add?___

* Interactivity by deciding and creating minimum representation of UI states

___What are the three questions you can ask to determine if something is state?___

1. Is it passed from a parent via props? Then probably not in state

2. Does it remain unchanged over time? Probably not in state

3. Can we compute it based on other state or props within component? Then probably not in state. 

___How can you identify where state needs to live___?

1. Identify every component rendering something based off that state

2. Find a common owner component (this component should live above all components needng the state)

3. If no higher such component exists, we can create a component solely for holding state.

---

## [Higher-order functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

___What is a “higher-order function”?___

* A higher-order function is a function operating on another function (taking them as arguments or returning them)

___Explain how either map or reduce operates, with regards to higher-order functions.___

1. Map: is a method that transforms an array by applying function within on all of its elements and returning a new array that has same length as unchanged input array. The first parameter in method is callback function thus making ArrayMap a higher-order function.

---

<===== [BACK!](README.md)
