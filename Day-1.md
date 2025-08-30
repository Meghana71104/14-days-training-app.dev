// First Day : Started learning with Js : <script> tag //
<script>
document.getElementById("demo").innerHTML = "My First JavaScript";
</script>
// This tag is used to write java scfipt inside html <head> or <body> tag //
// <head> example : //
<html>
<head>
<script>
function myFunction() {
  document.getElementById("demo").innerHTML = "Paragraph changed.";
}
</script>
</head> 
</html>

// <body> example : //
<!DOCTYPE html>
<html>
<body>

<h2>Demo JavaScript in Body</h2>

<p id="demo">A Paragraph.</p>

<button type="button" onclick="myFunction()">Try it</button>

<script>
function myFunction() {
  document.getElementById("demo").innerHTML = "Paragraph changed.";
}
</script>

</body>
</html> 

// External java script files can be written and linked to html file using script tag //
<script src="myScript1.js"></script>
<script src="myScript2.js"></script>

/* Writing into an HTML element, using innerHTML or innerText. 
Writing into the HTML output using document.write().
Writing into an alert box, using window.alert().
Writing into the browser console, using console.log() */

// using the innerHTML property we can change the HTML content of the HTML element //
<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = "<h2>Hello World</h2>";
</script>
// Initially paragraph tag dosen't have any html content in it, By using inner html I've changed it to have h2 element with some content in it //

// using the innerText property we can change the inner text of the HTML element: //
<p id="demo"></p>

<script>
document.getElementById("demo").innerText = "Hello World";
</script>
// Initially the paragraph tag dosen't have any elements, so innertext of an empty paragraph tag returns and empty string //
// Inner text of a paragraph tag with some elements present inside will return the text content of that element //
// From the above example "Hello World" will be displayed //

// document.write() //
// Example //
<script>
document.write(5 + 6);
</script>
// Displays the particlar output for the applied logic on the web page //
// Convenient to use for testing purpose //


// window.alert() //
<script>
window.alert(5 + 6);
</script>
// It is used to show/display the given content as a pop-up message //
// Example ://
<script>
window.alert(5 + 6);
</script>
// So, this will display "11" in the pop-up, i.e, the logic is being executed //

// console.log() //
<script>
console.log(5 + 6);
</script>
// A printing statement //
// It is used for the developers to use the output in console //

// Statements //
let x, y, z;    // Statement 1
x = 5;          // Statement 2
y = 6;          // Statement 3
z = x + y;      // Statement 4
// In a programming language, these programming instructions are called statements.//
// A JavaScript program is a list of programming statements. //
// A statement contains Values, Operators, Expressions, Keywords, and Comments. //


// Semicolons ; //
let a, b, c;  // Declare 3 variables
a = 5;        // Assign the value 5 to a
b = 6;        // Assign the value 6 to b
c = a + b;    // Assign the sum of a and b to c
// We add a semicolon at the end of each executable statement. //
// When separated by semicolons, multiple statements on one line are allowed. //
a = 5; b = 6; c = a + b;

// Code Blocks : //
// JavaScript statements can be grouped together in code blocks, inside curly brackets {...}.//
// Mostly used in writing functions in javascript. //
// Example : //
function myFunction() {
  document.getElementById("demo1").innerHTML = "Hello Dolly!";
  document.getElementById("demo2").innerHTML = "How are you?";
}
// The complete block is executed with each statement at a time //


// Keywords : //
// Keywords are unique names/Identifiers used to perform any particular javascript actions //
// Some of Keywords //
// var:Declares a variable //
var x, y;
x = 5 + 6;
y = x * 10;
//let:Declares a block variable//
let x, y;
x = 5 + 6;
y = x * 10;
// const:Declares a block constant//
const x = 5;
const y = 6;
const z = x + y;
// function:Declares a function //


/* Java script values : 
consists of two types :
1. Fixed values 
2. Variable values

Fixed values are called literals.
Variable values are called Variables.

Numbers - example : Not be written in quotes. */
10.50
1001

//String - example : Should be written within single or double quotes '' or " " . //
"Simon" 'Simon'
"Monica" 'Monica'

/* Variables : 
Used to store data 
var, let, const are used to declare variables.
"=" is used to assign values. */
let x;
x = 6;

let x = 5 ;
console.log(x);
x = 6 ;
console,log(x);
// Cannot be re-declared but allows to change the value it is not constant. //

/* Operators : 
Js uses arthimetic operators used to perform mathematical operations such as : (+,-,*,/) to compute values. */
let x = (5+6)*10
console.log(x)
// This will print 110 as the output. //

let x, y;
x = 5;
y = 6;
// Example for assignment operator. //


// Declaring variable : Creating a variable in Js is called "declaring". //
var carName;
let carName;

//After declaration if the variable does not hold any value (initialize) it is called undefined. //
 
// To initialize or assign a value we use "=" sign . Example : //
carName = "Toyota" ;
// Variables are case sensitive so, "carName" and "carname" are two different variables. //

// We can directly initialize the value during declaration Ex: //
let carName = "Toyota" ;

// We can declare many variables in a single line with a comma ",". Example: //
let person = "John Doe", carName = "Volvo", price = 200;

// Can also be in multiple lines . Example: //
let person = "John Doe",
carName = "Volvo",
price = 200;

// Data Types in Js : //
/* String	A text of characters enclosed in quotes
Number	A number representing a mathematical value
Bigint	A number representing a large integer
Boolean	A data type representing true or false
Undefined	A primitive variable with no assigned value
Null	A primitive value representing object absence
Symbol	A unique and primitive identifier
Object	A collection of key-value pairs of data */
// Examples : //
// Numbers:
let length = 16;
let weight = 7.5;

// Strings:
let color = "Yellow";
let lastName = "Johnson";

// Booleans
let x = true;
let y = false;

// Object:
const person = {firstName:"John", lastName:"Doe"};

// Array object:
const cars = ["Saab", "Volvo", "BMW"];

// Date object:
const date = new Date("2022-03-25");
