# Problem Domain, Objects, and The DOM

<!-- From the Duckett JS book:

Chapter 3: “Object Literals” (pp.100-105)
Chapter 5: “Document Object Model” (pp.183-242) -->

## [Understanding Problem Domain](https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming)

Often this ability to understand a problem domain is the primary factor getting in the way for people in programming.

* Make the problem domain easier

* Get better at understanding problem domain

## Primitive Values Vs Object References

### Value vs reference

primitive ___values___ are assigned to a value directly

* `const moe = 'MOE'`

* cannot be changed (immutable)

___Objects___ do not assign a value but instead a reference to a value.

* Values can be changed (mutated)

### Primitive Values

  1. Boolean
  2. Null
  3. Undefined
  4. Number
  5. BigInt
  6. String
  7. Symbol

### Object References

  1. Arrays
  2. Functions
  3. Dates

---

## JS Chapter 3 : Object Literals

* Object: an object is a set of variables and functions

In an object:

* _variables become properties_

* _Functions become methods_

### Creating Object Literal Notation

Easiest and most popular way to make objects

```
var hotel = {
  name: 'Quay`,
  rooms: 40,
  booked: 25,

  checkAvailability: function() {
    return this.rooms - this.booked;
  }
};
```

## JS Chapter 5 : Document Object Model

DOM specifies how browsers should create HTML model

* this allows JS so access and update content while it's on webpage.

* DOM Tree : Model of your webpage

### How to  access and edit DOM?

1. Locate node of element we are interested in

2. use text content, child elements, and attributes from the element.

---

## Questions to Answer After Reading

### Describe Object Literals in JavaScript

* an ___OBJECT___ in JavaScript is just a type of value in JavaScript that may have connections with other values.

* an ___OBJECT LITERAL___ is just an object value that we ___literally___ write into program or app.

  * Usually consists of a comma separated list of key-value pairs enclosed in curly brackets.

### Describe Dot and Bracket Notation for JavaScript Objects

  We can use either method to access property of an object, but what's the difference?

#### ___Dot Notation:___ Most used and more readable notation

* Not used when:

  * property name starts with numbers

  * property name is a "string"


Syntax: `objName.propertyName;`

#### ___Bracket Notation:___ Used when identifier starts with numbers or is a string

* used when:

  * property name has invalid identifier (starts with number or contains symbols)

  * property name is a "string"

    Syntax: `objName[123];`
  
* What is the DOM?

  * Document Object Model: This is the data representation of structure and content on a webpage. This DOM programming interface allows us to create programs that can change document structure, style, and content.

* What is DOM manipulation

  * DOM manipulation is the use of JavaScript to manipulate the webpage in our browser

* What are JavaScript objects

  * They are sets of variables and functions that are defined(or created) through object literals
  
    ```JavaScript
    const michael = {
      firstName: "Michael",
      lastName: "Maker",
      age: 27,
      fullName: function(){
        return `${this.firstName} ${this.lastName}, It's great to finally meet you...`
      }
      multipliedName: () => return `${firstName}`*5

    ```

* What are JavaScript methods?

  * A JavaScript Method is a function stored as a property within an object

    * We access these object methods with the following syntax:

    ```JavaScript
    objectName.methodName();
    ```

<===== [BACK!](README.md)
