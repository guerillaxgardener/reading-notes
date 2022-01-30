# HTML Tables; JS Constructor Functions

## [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

* The process of laying out a way to solve your specific problem with a conceptual model to be used as a map of sorts.

  * Doing this well can really help us to articulate the problem we're attempting to solve.

### Tips for building our domain models

1. Build ___self-contained object___ with the same attributes and behaviors when modeling a single entity for a specific problem.

2. Model its ___attributes___ with a constructor function that defines and initializes properties

3. Model it's ___behavior___ with small methods that focus on doing one job well

4. Use the `new` keyword followed by call to a constructor function to create ___instances___

5. Store new object in a variable to access methods and properties from outside

6. Use `this` variable within methods so you can access objects properties and methods from inside.

---

## CH 6 HTML Tables

##### Duckett HTML/ CSS Textbook (pp126-145)

A table is a convenient way to display some data types by separating it into a grid format.

### How to create tables

* written out ___ROW by ROW___
* `<table>` element used to create the table
* `<tr>` (table row) opening tag denotes the start of a new row
* `<td>` each cell of a table is represented by Table Data element
* `<th>` Table Heading element used to represent a row or column header
* `<colspan>` attribute can be used on th or td elements to indicate them spanning multiple columns
* `<rowspan>` attribute to make th or td span more than one row
* `<thead>` heading items should sit inside this element
*`<tbody>`body of table should live here
* `<tfoot>` footer lives here

---

## CH 3 Functions, Methods, and Objects

##### Duckett JS Book

### Creating an Object: ___CONSTRUCTOR___

```JavaScript
var cats = new Object();
// ^^^^ object
hotel.name = 'Quay';
hotel.rooms = 40;
hotel.booked = 25;
// ^^^ Key-value pairs (properties)
hotel.checkAvailablity = function(){
  return this.rooms - this.booked;
// ^^^ Method (function inside constructor)
};
```

### Updating object

* Use dot notation

* Use square brackets

```JavaScript
hotel.name = 'Park';
// obj.property_name = property value;
//    ^ member oper. ^ assignment operator
//  orrrrrrr.......


hotel['name'] = 'Park';
```

### THIS (THE KEYWORD)

Commonly used inside functions and objects.
Refers to object in which the function operates.

### Arrays are objects

* They are a special type of object holding related set of key/value pairs (like all objects)
* key for all values are their corresponding index values

### Three groups of Built-In Objects

1. Document Object Model: creates a model of the current web page.

2. Browser Object Model: creates a model of browser tab/window

3. Global JavaScript Objects: Group of objects often starting with capital letter.

* string: working with strings

* number: working with numbers

* boolean: working with boolean values

* date: handle dates

* math: calculations

* regex: match patterns in strings

<===== [BACK!](README.md)