# Basics of HTML, CSS, and JavaScript

## HTML Chapter 2 : Text

### Adding Markup text to our pages allows us to ellaborate on our
>
>* ___Structural Markup___ : we'll use these for describing headings and paragraphs
>
>* ___Semantic Markup___ : Provides amplifying info on somrthing within your webpage.

### Headings `<h1>, <h2>,...,<h6>`

>There are six headings within HTML. These are pre-set font sizes that aid in formatting our pages in a way easier for user to take in information; can be further styled and fine tuned.

### Paragraphs `<p> </p>`

> Paragraphs are used to divide between blocks of text on page with blank white space in order to make it easier for user to process.

### Bold & Italicized

> `<b>` enclosing in here will make text ____bold____ `</b>`
>
> `<i>` Text enclosed in these will be *itacized* `</i>`

### Line Breaks and Horizontal Rules

> ___Line Breaks___ : use `<br />` in order to create a line break within a paragraph
>
> ___Horizontal Rules___ : use `<hr />` in order to create a horizontal line on page used for a hard change of theme or topic.

### Strong and Emphasis 

> ___Strong___ : enclosing text within `<strong>` ___brackets will denote importance of text and make text bold___ `</strong>`
>
> ___Emphasis___ : Surrounding text in `<em>` tags will make text become italicized to denote emphasis `</em>`

### Quotations

> ___Blockquote___ : used for a long quote that takes up an entire paragraph.
>> EX: `<blockquote cite="http://examplesource.mic">`
`<p>` This is where the quote goes `</p>`

### Changing Content

> Insert Content : `<ins>` is used to show when we insert text 
>
> Delete Content : `<del>` is used to line out words and show their deletion.
>> Strikethrough also does similar function `<s>`


___

## HTML Chapter 10 : Introducing CSS

### What CSS Does

>CSS (Cascading style sheets) allow us to creat rules that govern layout and properties of elements on site

### How CSS Works
>
>CSS works by manipulating invisble boxes surrounding each HTML element.
>
> ### Rules, Properties, and Values
>
> * #### ___Rules___ : CSS rule has a selector that specifies HTML element to be manipulated, and a declaration that states the property and value being styled
>
>* #### ___Properties___ : This is the feature being manipulated
>
>* #### ___Values___ : This is the value of the manipulation being commited

___
___

## JS Chapter 2 : Basic JavaScript Instructions

### Syntax of JS
>
>JavaScript is made up of scripts which are instructions to the computer
>> EX: `var today = new Date();`
>>
>> EX: `if (hourNow > 18) {greeting = "good evening"};`
>>
> JavaScript is *___CASE SENSITIVE!___*
>
> ___Comments___ : 
> * single line: `//display time of day.`
>
> * Multi-line: `/* lots of beautiful multi-line text will go here when you write sweet memo novels to your friends in the not so private privacy of your repositories. */`

### Variables
>
>Data that can be stored under custom values for later use wihin code.
>
> Variables are made up of the variable keyword and then the variable name.
>
>> EX: `var quantity;`
>
> Assinging a variable : made up of variable name set equal tpo value
>> EX: `quantity = 3;`

### Data Types
>Number: 1,2,3,4
>
>String: 'hello pal!' or '17'
>
>Boolean: True or False

### Array
>
> an array stores an entire list of variables while a variable only stores one value

### Operators

> Arithmetic operators manipulate numbers
>
>String operators can perform concatenation and add strings together or take them away.
___

## JS Chapter 4 : Decisions and Loops

### Evaluations
>Allow us to check measured values in code and compare with expected results
>
> Comparison Operators are used within evaluations
>> `==` means 'equal to'
>>
>> `!=` means 'not equal to'
>>
>>`===` means 'strictly equal to'
>>
>> `!==` means 'strict not equal to'
>
> Logical Operators
>> `&&` means 'logical and'
>>
>> `||` means 'logical or'
>>
>> `!` means 'logical not'

### Decisions
>This uses the data from evaluations to make decisions on which direction the flow chart of code shall take.

### Loops
>We use loops when we want a task to perform multiple steps on repeat

[<===== BACK!](README.md)