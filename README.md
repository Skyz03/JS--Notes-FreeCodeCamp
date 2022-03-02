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

#### Read-Only Variable with the const Keyword
const has all the awesome features that let has, with the added bonus that variables declared using const are read-only. They are a constant value, which means that once a variable is assigned with const, it cannot be ```reassigned```.
It is common for developers to use uppercase variable identifiers for immutable values and lowercase or camelCase for mutable values.

### Numbers
Number is a data type in JavaScript which represents numeric data.
const myVar = 5 + 10;
const myVar = 12 - 6;
const myVar = 13 * 13;
const myVar = 13 * 13;
const myVar = 16 / 2;
i++; ```i = i + 1;```
i--; ```i = i - 1;```

Decimal numbers are sometimes referred to as floating point numbers or floats.
const myDecimal = 5.8;

#### Remainder in JavaScript
The remainder operator % gives the remainder of the division of two numbers.

#### Odd Even Checker
17 % 2 = 1 (17 is Odd)
48 % 2 = 0 (48 is Even)

#### Augmented Arguments(Addition/Sub/Multi/Divide)
One such operator is the += operator.

let myVar = 1;
myVar += 5;
console.log(myVar);

6 would be displayed in the console.

### Escaping Literal Quotes in Strings
In JavaScript, you can escape a quote from considering it as an end of string quote by placing a backslash (\) in front of the quote.
const sampleStr = "Alan said, \"Peter is learning JavaScript\".";

### Escape Sequences in Strings

Quotes are not the only characters that can be escaped inside a string. There are two reasons to use escaping characters:

    To allow you to use characters you may not otherwise be able to type out, such as a carriage return.
    To allow you to represent multiple quotes in a string without JavaScript misinterpreting what you mean.

We learned this in the previous challenge.
Code	Output
\'	single quote
\"	double quote
\\	backslash
\n	newline
\r	carriage return
\t	tab
\b	word boundary
\f	form feed

Note that the backslash itself must be escaped in order to display as a backslash.

### Concatenation
const ourStr = "I come first. " + "I come second.";

### Concatenating Strings with the Plus Equals Operator
We can also use the += operator to concatenate a string onto the end of an existing string variable. This can be very helpful to break a long string over several lines.
```let myString = "One";
myString += "Two";
```

### Strings with Variables
const ourName = "freeCodeCamp";
const ourStr = "Hello, our name is " + ourName + ", how are you?";

### Appending Variables to Strings
const anAdjective = "awesome!";
let ourStr = "freeCodeCamp is ";
ourStr += anAdjective;

### Length of a String
console.log("Alan Peter".length);

#### Bracket Notation
Bracket notation is a way to get a character at a specific index within a string.
const firstName = "Charles";
const firstLetter = firstName[0];

firstLetter would have a value of the string C.

### String Immutability
In JavaScript, String values are immutable, which means that they cannot be altered once created.
let myStr = "Bob";
myStr[0] = "J";

This does not mean that myStr cannot be changed, just that the individual characters of a string literal cannot be changed. The only way to change myStr would be to assign it with a new string, like this:

let myStr = "Bob";
myStr = "Job";


