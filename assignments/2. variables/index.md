1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark";
```
<!-- name is variable -->

2. Find the error if any
```js
  var product cost = 3.45;
```
<!-- var can have only one word i.e without spaces  -->

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" - right
  'Hello World" - wrong
  "Hello World' - wrong
  'Hello World' - right
```


## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man;    - VALID
var 1girl;  - INVALID
var woman3; - VALID
var -girl;  - INVALID
var blackDog; - VALID
var 42;     - INVALID
var $42;    - VALID
var userName; - VALID
var x, y, z; - VALID
var x = 5, y = 6, z = 7; - VALID
var x = 5 + 10 + 2; - VALID
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var amount = 2080;
var sub = 2080-80;
alert(sub);
// Define a new variable and store the value that is 200 more then the value of amount.
var amount = 2080;
var sum = 2080+200;
alert(sum);
// Define a new variable and store the value that is 4 times the value of amount.
var amount = 2080;
var mul = 2080*4;
alert(mul);
// Define a new variable and store the reminder when the value of amount is  divided by 21.
```
var amount = 2080;
var div = 2080/21;
alert(div);



Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark
var johnAge = 45;
var markAge = 35;
if (johnAge>markAge) alert("John is older than Mark");
else alert("Mark is older than John");

// Check who is younger
var johnAge = 85;
var markAge = 65;
if (johnAge<markAge) alert("John is younger than Mark");
else alert("Mark is younger than John");

// Check if their age is equal
var johnAge = 65;
var markAge = 65;
if (johnAge == markAge) alert("John's age is equal to Mark's");
else alert("John's age is NOT equal to Mark's");

// Create a new variable and assign the age of john to new variable.
var johnAge = 69;
var markAge = 65;
var newvar = johnAge;
alert(newvar);
// Check if john is equal to or greater then mark.
var johnAge = 65;
var markAge = 65;
if (johnAge >= markAge) alert("John's age is greater than or equal to Mark's");
else alert("John's age is less than Mark's");
// Check if john is less then or equal to mark.
var johnAge = 65;
var markAge = 65;
if (johnAge <= markAge) alert("John's age is less than or equal to Mark's");
else alert("John's age is greater than Mark's");
// Calculate the average age of john and mark and assign to a new variable.
var johnAge = 50;
var markAge = 65;
var avgAge = (johnAge+markAge)/2;
alert("Average age = " +avgAge);
```
