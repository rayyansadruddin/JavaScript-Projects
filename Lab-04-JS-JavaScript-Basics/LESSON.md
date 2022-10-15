# Notes (Basics)

### Comments / Header

When we begin writing code, it's important to write *comments* throughout to explain what your code is doing.  This is both for you and for anybody that is trying to read your code!

In JavaScript we use the ```//``` sign at the beginning of a line to tell the intrepeter to ignore it.

```JavaScript
// This is a single line comment!
This is not a comment!
/*
This is a multi-line comment!
*/
```

At the top of each program we'll include a *header* - same idea as having a title page (name, date, etc).

### Printing to console

When printing strings (text), you need to use a set of quotation marks around the string you want to print (i.e. "What's going on?").  

```JavaScript
console.log("Hello world!");
```

You can also print numbers on their own, or concatenate them with strings to create a piece of information that includes words and a calculation.

```JavaScript
console.log("The value of x is: " + 5.5);
console.log("The value of x is: " + 3*6);
```

### Variables, Constants and Printing

Variables are used to temporarily store information, and can be manipulated in multiple ways.  

Variables should be named so that it is easy to tell what the value held by the variable is. The naming convention for JavaScript is to use `camelCase` when creating variables that contain more than one word.

```JavaScript
// camelCase
myFirstInteger = 22;
```

Variables can be of different types such as:
* integers (whole number values)
* floats (can include decimal values)
* strings (text)
* Boolean values (true or false)
* and more!

In JavaScript we don't have to declare what type the variable is - the intrepeter will figure that out from what you assign it.

```JavaScript
let integerOne = 15;
let myFloat = 18.6;
let greeting = "Hello";
let myBool = false;
```

If you know a value has no need to change, you can instead create a constant:

```JavaScript
const PI = 3.14;
let radius = 5;

console.log("The area of the circle is: " + PI * radius);
```

Here are some examples of how to print out the information in the console.

```JavaScript
let result = 80;
console.log("The result of the calculation is: " + result);

message = "There";
console.log("Hello " + message);
```

### Mathematical Operations

You can use the standard mathematical operators ```+```, ```-```, ```*```, ```/``` as well as some other ones that you might not be used to using such as:

* ```%``` - This is used to find the remainder after a division (see below)
* ```**``` - This is used for a power (see below)

```JavaScript
moduloOfIntegers = 5 % 2;
console.log(moduloOfIntegers);  // Should be 1

powerOfIntegers = 2 ** 3;
console.log(powerOfIntegers);   // Should be 8
```

Make sure that you are doing math with integers or floats only - weird things happen when you do "math" with strings!

```JavaScript
console.log("5" * 3); // gives you 15
console.log("5a" * 3); // gives you NaN
```
