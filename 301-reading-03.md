# Code 301 Reading 3: Passing Functions as Props

## [Lists and Keys](https://reactjs.org/docs/lists-and-keys.html)

___What does .map() return?___

* Allows us to iterate through an array with a callback function applied to the arrays elements, and returns an array of the modified elements from the first array

___How do I loop through an array and display each value in JSX in React?___

* using javascript's .map() function

___Each list item needs a unique _.___

* Key

___What is the purpose of a key?___

* A special string attribute needed when creating lists of elements, they help React identify which items have changed, are added, or are removed; this gives elements in an array stable identities.

* A good rule of thumb is assuming elements inside a `.map()` call need a key.

```JavaScript
const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((number) =>
  <li key={number.toString()}>
    {number}
  </li>
);
```

^ direct quoted code from <https://reactjs.org/docs/lists-and-keys.html>

---

## [How to Use the Spread Operator in JS](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

___What is the spread operator?___

* The ___Spread Operator___ is a simple syntax used in JavaScript that expands an iterable object, usually strings.

___List 4 things that the spread operator can do.___

1. Copying an array
2. Using Math functions
3. Combining objects
4. Concatenating or combining of arrays

___Give an example of using the spread operator to combine two arrays.___

```JavaScript
'use strict';
const michael = ['🍏','🍊','🍌','🍉','🍍']
const maker = ["I","love", "fruit"]
const michaelMaker = [...michael, ...maker]
console.log(michaelMaker);

//RETURNS COMBINED ARRAY
// [object Array] (8)
["🍏","🍊","🍌","🍉","🍍","I","love","fruit"]

```

___Give an example of using the spread operator to add a new item to an array.___

```JavaScript
'use strict';
let michaelsFruit= ['🍏','🍊','🍌','🍉','🍍']
let michaelsFruitPlusWords = ["I","love", "fruit", ...michaelsFruit]
console.log(michaelsFruitPlusWords)

//RETURNS COMBINED ARRAY
// [object Array] (8)
["I","love","fruit","🍏","🍊","🍌","🍉","🍍"]
```

___Give an example of using the spread operator to combine two objects into one.___

```JavaScript
'use strict';
let objectOne = {bark: "true"}
let objectTwo = {meow: "true"}
let objectThree = {...objectOne, ...objectTwo}

console.log(objectThree);


//RETURNS COMBINED OBJECTS
```

---

## [Passing Function Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

___In the video, what is the first step that the developer does to pass functions between components?___

First we will create our function wherever the parent state component is, we'll use this to render changes and then setState of parent.

___In your own words, what does the increment function do?___

The increment function created in the video takes in a persons name, find matching name, uses .map() to create a new array and then passes that array with updated increment to count, then sets this to 'ppl' variable and uses setState to update state and then we use prop to pass up to original object which gives us state change and we re-render.

___How can you pass a method from a parent component into a child component?___

Using a state change that effects child component

___How does the child component invoke a method that was passed to it from a parent component?___

  ``` JavaScript
  this.props.increment(this.props.name) 
  ```
  
  ^^^ is used within function created under parent function with that 'increment' function or whatever else we've called it, taking being called or receiving input from somewhere within child component.

---

<===== [BACK!](README.md)
