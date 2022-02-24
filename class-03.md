# HTML Lists, Control Flow with JS, and the CSS Box Model

## HTML Lists

##### Duckett HTML/ CSS Textbook

Ordered Lists : Numbered lists.

* `<ol>` creates list

* `<li>` line item in list

  * Browser indents list.
  
Unordered Lists: Bullet points.

Definiton Lists: Terms with definitions.

We can nest lists within each other!

---

## CSS Boxes

##### Duckett HTML/ CSS Textbook

### CSS 
  
* treats all elements it contains as being contianed in their own individual boxes
* CSS controls many dimensions of boxes.
* CSS allows for customization of features for each 'box' like:
  * Borders
  * Margin
  * Padding

Block and inline boxes may be converted into one another to stack individual boxes vertcally or horizontally.

CSS3 has ability to create image borders and to round our border corners in interesting ways.

## Basic JavaScript Instructions

##### Duckett JS Textbook

### Arrays special veriable type storng a list of values in many ways.

```JavaScript
 var colors;
  colors = [red, blues, black];


  //update third item in array
  colors[2] = 'orange';
```

---

## Decisions and Loops

##### Duckett JS Textbook 162-182

### if... else statements

```JavaScript
 if (score >= 50) {
    congratulate();   //code to execute if true
    } else  {
    encourage();
    }
```




### Switch Statements

* start with a switch value and different cases determine which code will run based off variables matching to value

```JavaScript
 switch (level) {

   case 'One':
     title = 'Level 1';
     break;

    case 'Two':
      title = 'Level 2';
      break;

    default:
      title = 'Test';
      break;
 }
```

### Loops check a condition and runs repeatedly until some condition listed within returns false

#### For Loops: used to run code for a specific quantity of loops

```JavaScript
for (var i = 0; i < 10;; i++) {
  document.write(i);
}
```

#### While Loops: Used when we do not know how many times a code should be cycled through; not a counter and will loop so long as a condition stated is true

```Javascript
while (i < 10){
  msg += i + ' x 5 ' + (i*5) + '<br />';
}
```

#### Do while loop: Similar operation to the While Loop, but will run through all code in curly brackets one time at least even if condition evaluates to false

<=====[ BACK!](README.md)