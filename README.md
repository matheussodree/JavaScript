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
Operator | Function       | Example
   ==    | Equal to       | (x == y)
   !=    | Not equal to   | (x != y)
   ===   | Identical to   | (x === y)
   !==   | Not Identical to |(x !== y)
   >     | Greater than   |(x > y)
   >=    | Greater than or equal to |(x >= y)
   <     | Less than      | (x < y)
   <=    | Less than or equal to | (x <= y)

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
