# Reading 4  HTML Links, JS Functions, and Intro to CSS Layout

---

## HTML Links

* Very important tool enabling us to travel around the web

##### Duckett HTML/ CSS Textbook

Created with `<a>` element. and specify page with href

### Types of common links:

* Links between pages

* Linking to other sites

* Email Links

---

## HTML Layout

##### Duckett HTML/ CSS Textbook

### HTML Building Blocks

<div> element often used to contain a similar grouping of elements.

#### Block-Level Elements : Same line content

```HTML
* <h1>

* <p>

* <ul>

* <li>
```

#### Inline Elements : Flow in between text

```HTML

* <img>

* <b>

* <i>
```

### CSS Element Positioning

Browsers will default to normal flow without specification.

* Normal Flow: Every block element will receive its own line

* Relative Positioning: Shifts elements around without affecting surroundings

* Absolute Positioning: positions in relaton to containing element without affecting surrounding elements.

* Floating an element allows us to just place it on a sde of a box.

### Page Size

Commonly between 960-1000 px wide and talk of pages purpose in first 600px height to fit on most monitors and give quick info.

a good CSS framework provides rules for common tasking done repeatedly.

### Grids

Allow us to create professional and flexible design simply with our webpages.

---

## Functions, Methods, and Objects 86-99

##### Duckett JS Textbook

### JavaScript Function

Lets you group many statements together to perform a specific task.

```JavaScript
function = updateMessage() {    //this top group of info is the FUNCTION DECLARATON
  var el = document.getElementById('message');
  el.textContent = msg
}
updateMessage();      //here we are calling the function
```

* parameters are just variables within functions.

* to receive a value from a function, assign value to variable and then return variable.

* to receive multiple value returns, use an array inside variable.

#### Local vs Global Scopes:

* Local Variables : created with `var` inside function and only exists within functon's scope

* Global Variables: created outside function and can be used throughout your script.

## Reasons for Pair Programming

* Pair programming is so valuable because we are working many types of development skills:

  * Listening
  * Speaking
  * Reading
  * Writing

* May aid in increased code efficiency than each dev separately.
* Engaged constantly in collaborating
* Learning from one another to strengthen team
* Prepares us for job search
* Prepares us for our future work environments

<>===== [BACK!](README.md)