# JS
-------

## Glossary
 
### Argument
Values passed into a function. Listed in the function call.

```Javascript
iDontCare(argument);
```

### Assignment
Operation that sets a var, let, or const to something.

```Javascript
let foo = 0;
```

### Binary Operators
Does operation such as add, subtract, etc. Also logical.

```Javascript
a + b; 
  ^
this && that
```

### Binding
See Assignment.

### Block
A group of statements that becomes one statement surrounded by { }.

```Javascript
//Block using if statement
if (value == x) {
	do this.
}
```

### Boolean
A true or false value, internally denoted as 0 or 1. Also, see truthy and falsy.

### Composition
Using functions inside of functions to force a run order. See also Callback Functions.

```Javascript

```

### Condition
A statement stating the logic to be evaluated. 
```Javascript
//Check condition
if (x == y)
//  ^ condition in parenthesis
```

### Do Loop
Like while loop but will do at least one time.

```Javascript
do {
//Something Happens here, at least once.
} while (condition);
```

### Expression
A fragment of code that produces a value.

```Javascript
x = 5;
```

### Falsy Values
Values that are equivalent to FALSE.

```Javascript
if (false)
if (null)
if (undefined)
if (0)
if (NaN)
if ('')
if ("")
if (document.all) [1]
```

### Loop
A code block that repeats code until the specified condition is met.

### Method
A pre-defined way of manipulating an object.

```Javascript
array = array.push("this")
```

### Object
tk 

### Parameters
Sometimes interchangeable with Arguments. These are the values listed at the top of the function that are passed in. 

```Javascript
function iDontCare (params) {
	
}
```

### Pure Method
A method with a forced return and no side-effects. i.e. no console logs, etc.
### Refactor
Modifying code so it is more concise and readable.

### Ternary Operators
Runs test against condition and based on bool, spits out one of two responses.

### Truthy Values
Values that are equivalent to TRUE.

```Javascript
if (true)
if ({})
if ([])
if (42)
if ("foo")
if (new Date())
if (-42)
if (3.14)
if (-3.14)
if (Infinity)
if (-Infinity)
```

### Unary Operators
One transformation of a value. 
```Javascript
i++
i--
```

### While Loop 
Runs code block while condition is true.

```Javascript
while (condition) {
	
}
```






## Pure Methods

### Map
Take input and transform into new array.
	
```Javascript
input = [1, 2, 10, 16, 20];
const mapArray = array.map(input => input + 1000); 
//output = [1001, 1002, 1010, 1016, 1020]
```
	
### Filter
Take input and filter for TRUE.
```Javascript
input = [5, 100, 5000, 157424, 2]; 
const filterArray = array.filter(input => input >= 1000);
// output = [5000, 157424]
```

### Reduce
Essentially the same as Sum Function in Excel
```Javascript
input= [1, 2, 10, 16, 20];
const reduceArray = array.reduce((acc, num) => {return acc + num}, -25);
// Internally, accumulator starts at -25, then starts adding the numbers in the input array to it and outputs when done.
// So, in this example, internally, it is -25 + 1 + 2 + 10 + 16 + 20.
// output = [24]
```

