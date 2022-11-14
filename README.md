# _JavaScript_
_JavaScript documentation_

* Console.log
~~~javascript
console.log("Hello World");
~~~

* Alert
~~~javascript
alert("Hello world");
~~~

* Var 
~~~javascript
var x = "string"
var y = 1 (number)
var z = boolean (true or false)
~~~

* Let
~~~javascript
let x = "string"
let y = 1 (number)
let z = boolean (true or false)
~~~

* Const
~~~javascript
const x = "string"
const y = 1 (number)
const z = boolean (true or false)
~~~

* Template Strings
~~~javascript
console.log(`Hello ${var} World`)
~~~

* Comments in JavaScript

/*

 Hello World
 
*/ 

* Comments Inline

// hello world

* If and Else commands
~~~javascript
if(condition){
   "line of code"
}else if(condition){
   "line of code"
}else{
   "line of code"
}
~~~

* parseInt or parseFloat
~~~javascript
parseInt(); "Remove the fractional part of the number"
parseFloat(); "Preserves the fractional part of the number"
toString(); "Remove from type number and convert to string"
~~~

* querySelector
~~~javascript
document.querySelector("h1" or " .class " or " #id ");
~~~

* Switch command
~~~javascript
meets identical parameters:

switch(option){

case 1 :
     code
break

case 2 :
     code
break

default :
    code
}
~~~

* Fuctions 
~~~javascript

Encapsulate a block of code with a defined purpose
ex:
function calculateGroundArea(width, length){
   var area = width * lenght
   
   return area
}

~~~

* Arrays
~~~javascript

In JavaScript, Arrays are objects with their own methods.
An Array object is used to store a collection of items in a single variable.

Example:
var arr = new Array();
// Because it is an object we can use "new" in its creation

var arr = new Array(elem1,elem2, ... ,elemN);
// This way we create an array already started with elements.

var arr = [1,2,3,4];
// another way is to start an array with elements without using "new".

var arr = new Array(4);
// This way we create an empty 4-position array.

To access the variables inside an array, 
just use the name of the array and the index of the variable you want to access.

Example:
arr[0] = "Goodbye and thanks for the fish";
arr[1] = 42;
document.write(arr[1]);
//print the content of arr[1]

~~~

* Operators

In this section we will list the main operators that make up the core of the JavaScript language
~~~javascript

Arithmetic
Operator| Operation       | Example
   +    | addition        | x+y
   -    | subtraction     | x-y
   *    | multiplication  | x*y
   /    | division        | x/y
   %    | Modulus         | x%y
   -    | Sign inversion  | -x
  ++    | Increment       | x++ or ++x
  --    | Decrement       | x-- or --x

obs: Modulus (remainder of integer division)
~~~

~~~javascript

Comparation
Operator |         Function         | Example
   ==    |         Equal to         | (x == y)
   !=    |       Not equal to       | (x != y)
   ===   |       Identical to       | (x === y)
   !==   |     Not Identical to     | (x !== y)
   >     |      Greater than        | (x > y)
   >=    | Greater than or equal to | (x >= y)
   <     |        Less than         | (x < y)
   <=    |   Less than or equal to  | (x <= y)

obs: identical = (equal and of the same type)
~~~

~~~javascript

Bit by bit

Operator |      Operation     | Example
   &     |      E (AND)       | (x & y)
   |     |      OR (OR)       | (x | y)
   ˆ     | Exclusive Or (XOR) | (x ˆ y)
   ˜     |    Negation (NOT)  | ˜x

~~~

~~~javascript

Assignment
Operator | Example   | Equivalent
   =     |  x = 2    | does not have
  +=     |  x +=     | y x = x + y
  -=     |  x -= y   | x = x - y
  *=     |  x *= y   | x = x * y
  /=     |  x /= y   | x = x / y
  %=     |  x %= y   | x = x % y
  &=     |  x &= y   | x = x & y
  |=     |  x |= y   | x = x | and
  ˆ=     |  x ˆ= y   | x = x ˆ y
 >>=     |  x >>= y  | x = x >>= y
 <<=     |  x <<= y  | x = x <<= y
>>>=     |  x >>>= y | x = x >>>= y

~~~

~~~javascript

logical
Operator |     Function     |  Example
  &&     |    Logical AND   |  (x && y)
  ||     |    Logical OR    |  (x || y)
  !      | Logical negation |    !x

~~~

* Control Structures

if ... else Structure

~~~javascript
 
The if structure is used when you want to check whether a certain expression 
is true or not, and execute specific commands for each case.

if ... else structure
The if structure is used when you want to check whether a certain expression is true or not, 
and execute specific commands for each case.

Example 1

var a = 12;
var b = 5;
if (a == b) {
window.alert("12 equals 5?!?!");
} else {
window.alert("a is different from b");
}
// In the above case the written sentence would be "a is different from b"

Example 2

It is also possible to cluster more tests using the else if command

var a = 10;
if (a < 6) {
window.alert("less than 6");
} else if (a > 6) {
window.alert("greater than 6");
} else {
window.alert("if a is neither greater nor less than 6, a is 6!");
}

Example 3

Another possible way of using the " if " is with its abbreviated form as in the C language, 
using the ternary operator " ? " .
It can create simple decision structures in just one command line, however, 
this can often impair the clarity of your code, making it difficult to understand 
for someone unfamiliar with using this conditional operator.

var a = 8;

(a >= 5 ? window.alert("yes") : window.alert("no"));

// This is equivalent to the code:
var a = 5;
if (a >= 5) {
window.alert("yes");
} else {
window.alert("no");
}
~~~

Switch ... case
~~~javascript
Switch structures are used when we want to select an option among several available.
Unlike other languages, comparison values can be strings in addition to numeric values.

The break statement causes the switch to stop checking the other possibilities below 
and can be omitted if you want a structure that will make more than one option true.

Finally, default is optional and corresponds to a sequence of commands that 
will be executed when none of the others are.

Example : 

var marvin = "robot";
switch(marvin) {
   case "human":
      document.write("hello carbon unit!");
   break;
   case "alien":
      document.write("brrr I hate aliens!");
   break;
   case "robot":
      document.write("emergency, to the rescue!");
   break;
   default:
      document.write("what are you?");
   break;
}

~~~
