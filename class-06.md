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

* *variables become properties*

* *Functions become methods*

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

<>===== [BACK!](README.md)