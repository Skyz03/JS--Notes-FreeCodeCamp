# JS--Notes-FreeCodeCamp
This is a JavaScript Notes from the FreeCodeCamp Website Tutorials.

### Comment
Using // will tell JavaScript to ignore the remainder of the text on the current line. This is an in-line comment:

// This is an in-line comment.

You can make a multi-line comment beginning with /* and ending with */. This is a multi-line comment:

/* This is a
multi-line comment */

### Variables
JavaScript provides eight different data types which are ```undefined, null, boolean, string, symbol, bigint, number, and object```
Variables allow computers to store and manipulate data in a dynamic fashion.

### Operator
myVariable = 5;

### Assigning the Value of One Variable to Another
var myVar;
myVar = 5;
var myNum;
myNum = myVar;

### Strings
var myName = "First String";
"First String" is called a string literal. A string literal, or string, is a series of zero or more characters enclosed in single or double quotes.
When JavaScript variables are declared, they have an initial value of ```undefined.```
If you do a mathematical operation on an undefined variable your result will be NaN which means "Not a Number". If you concatenate a string with an undefined variable, you will get a literal string of undefined.
It is caseSensitive. 
MYVAR is not the same as MyVar nor myvar.

#### Differences Between the var and let Keywords
So unlike var, when you use let, a variable with the same name can only be declared once.

