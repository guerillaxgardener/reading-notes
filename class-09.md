# Reading 09 HTML Forms and JS Events

## CH 7 Forms (pp 144-175)

##### Duckett HTML Textbook

Forms are elements that allow someone to collect info from users of their site.

### Collecting info from visitors

 Can take in:
 * text
 * password
 * checkboxes
 * radio buttons
 * and much more!

### Form Structure
```HTML
<form action="URL for page receiving info when form submits" method="get or post may be used">
  <p>info on form </p>
  <input type = "text" name = "username">
```

## CH 14 Lists, Tables & Forms (pp 1330 357)

##### Duckett HTML Textbook


On top of CSS, there are several properties specifically for customizing lists, tables, and forms.

### Bullet Point Style

1. `list-style-type` decide type of bullet

2. `list-style-image` Use image as bullet

### Tables can have different..

* borders
* spacing

### Forms work best when vertically aligned in CSS and benefit from interactive styling.

---

## CH 6 Events (pp 243-292)

##### Duckett JS TextbookChapter 

## Event Handling

__Event:__ gets fired or raised to trigger the code

> Browser's way of indicating something has occured
>
> ex: click, submit, mouse over, mouse down, key press

__Code:__ Gets triggered

* Event Listener : listens for an event like clcking and activates the *event handler* code.

* Event Handler : Code that runs n response to event listener

### How WE SHALL DO THIS

> `element.addEventListener('event', callback function);` like "keyPress", "click", etc

* *Callback Function* = function that is passed in as an argument to another function

* declaring a function and passing n a callback will run callback functon along with other funtion.

> EX: `button.addEventListener('submit', handleSubmit)

___*Event Bubbling:*___ This is what we often see, which features overlapping bubbles of events

* ___Event listener___ will be placed on outter bubble (bubbles can be thought of as HTML section boxes)

### Binding

* process of connecting an event you're waiting to happen to the element that event will happen upon.

<===== [BACK!](README.md)