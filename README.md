# jsnote
JavaScript 
Concept JavaScript is a programming language that adds interactivity to your website.

The JS concepts we’ll be looking at:
 1. Scope
 2. IIFE
 3. MVC
 4. Async/await
 5. Closure
 6. Callback
Example
Let’s assume you create a function and want to access a variable defined in global scope.
. Variable:- A JavaScript variable is simply a name of storage location. There are two types of variables in JavaScript : local variable and global variable. There are some rules while declaring a JavaScript variable (also known as identifiers). Name must start with a letter (a to z or A to Z), underscore( _ ), or dollar( $ ) sign.
For example, var x; let y; Here, x and y are variables.
. Datatype :- In Javascript, there are five basic, or primitive, types of data. The five most basic types of data are strings, numbers, booleans, undefined, and null. We refer to these as primitive data types. A single variable can only store a single type of data.

Example Let name =“Tesfa”;

. Conditional statement:- Conditional statements control behavior in JavaScript and determine whether or not pieces of code can run. There are multiple different types of conditionals in JavaScript including: “If” statements: where if a condition is true it is used to specify execution for a block of code.

Example:- (10 > 5) is the condition to test, which in this case is true — 10 is greater than 5. The part contained inside curly braces {} is the block of code to run. Because the condition passes, the variable outcome is assigned the value "if block".

. Loops:- We will discuss about continue and break keywords used to control the loops execution.
 • The for loop statement. The for statement is used when you know how many times you want to execute a statement or a block of statements. ...
 • The while loop statement. ...
 • The do... ...
 • The foreach loop statement. ...
 • The break statement.
for example, if we want to print "Hello, World!" 10 times then instead of writing printing code for 10 times we can use a loop and write the code once.

for (var i = 1; i <= 10; i++) {
  console.log(i);
}

.Methods:- JavaScript methods are actions that can be performed on objects. A JavaScript method is a property containing a function definition. Methods are functions stored as object properties.

const person = {
  firstName: "John",
  lastName: "Doe",
  id: 5566,
  fullName: function() {
    return this.firstName + " " + this.lastName;
  }
};

. Dom:- The DOM (Document Object Model) is an interface that represents how your HTML and XML documents are read by the browser. It allows a language (JavaScript) to manipulate, structure, and style your website.

<html>
<body>

<p id="demo">Click the button to display the cookies associated with this document.</p>

<button onclick="myFunction()">Try it</button>

<script>
function myFunction() {
  document.getElementById("demo").innerHTML =
  "Cookies associated with this document: " + document.cookie;
}
</script>

. Event:- Events are actions or occurrences that happen in the system you are programming, which the system tells you about so your code can react to them. 

For example, if the user clicks a button on a webpage, you might want to react to that action by displaying an information box.
