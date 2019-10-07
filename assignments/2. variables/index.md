1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark";
//name is the variable assigned to the string "Mark"
```

2. Find the error if any
```js
  var product cost = 3.45;
//wrong syntax there should be one variable name assigned to the value 3.45 
```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" //Right
  'Hello World" //Wrong
  "Hello World' //Wrong
  'Hello World' //Right
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man;  //valid
var 1girl; //unvalid
var woman3; //valid
var -girl; //unvalid
var blackDog; //valid
var 42; //unvalid
var $42; //valid
var userName; //valid
var x, y, z; //valid
var x = 5, y = 6, z = 7; //valid
var x = 5 + 10 + 2; //valid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var newAmount = amount - 80;

// Define a new variable and store the value that is 200 more then the value of amount.
var newAmount = amount + 200;

// Define a new variable and store the value that is 4 times the value of amount.
var newAmount = 4*amount;

// Define a new variable and store the reminder when the value of amount is  divided by 21.
var newAmount = amount % 21;
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark
if(johnAge > markAge){
  console.log("John is older");
}else{
  console.log("Mark is older than John");
}
// Check who is younger
if(johnAge > markAge){
  console.log("Mark is younger");
}else{
  console.log("John is younger");
}
// Check if their age is equal
if(johnAge === markAge){
  console.log("John and Mark are the same age.");
}
// Create a new variable and assign the age of john to new variable.
var newJohn = johnAge;
// Check if john is equal to or greater then mark.
if(johnAge >= markAge){
  //code
}
// Check if john is less then or equal to mark.
johnAge <= markAge;
// Calculate the average age of john and mark and assign to a new variable.
var avgAge = (johnAge + markAge)/2;
```