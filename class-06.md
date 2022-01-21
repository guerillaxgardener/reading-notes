# Problem Domain, Objects, and The DOM

## [Understanding Problem Domain](https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming)

Often this ability to understand a problem domain is the primary factor getting in the way for people in programming.

* Make the problem domain easier

* Get better at understanding problem domain

## Primitive Values Vs Object References






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

===== [BACK!](README.md)