# JS Glossary

Argument - Values passed into a function. Listed in the function call.

Assignment - Operation that sets a var, let, or const to something.

Binary Operators - True/False comparisons.

Binding - See Assignment.

Block - A group of statements that becomes one statement surrounded by { }.

Boolean - A true or false value, internally denoted as 0 or 1.

Composition - Using functions inside of functions to force a run order

Condition - A statement stating the logic to be evaluated. 

Do Loop - Like while loop but will do at least one time.

Expression - A fragment of code that produces a value.

Loop - A code block that repeats code until the specified condition is met.

Method - A pre-defined way of manipulating an object.

Object - 

Parameters - See Argument. These are the values listed at the top of the function that are passed in. 

Pure Method - A method with a forced return and no side-effects. i.e. no console logs, etc.

Ternary Operators - Runs test against condition and based on bool, spits out one of two responses.

Unary Operators - One transformation of a value. ex. double = value + value

While Loop - Runs code block while condition is true.







## Pure Methods
```javascript
Map - Take input and transform into new array.
	Ex. const mapArray = array.map(input => input + 1000);
	Input= [1, 2, 10, 16, 20] 
	Output = [1001, 1002, 1010, 1016, 1020]
Filter - Take input and filter for TRUE.
	Ex. const filterArray = array.filter(input => input >= 1000);
	Input = [5, 100, 5000, 157424, 2] 
	Output = [5000, 157424]
Reduce - Essentially the same as Sum Function in Excel
	Ex. const reduceArray = array.reduce((acc, num) => {return acc + num}, -25);
		Internally, accumulator starts at -25, then starts adding the numbers in the input array to it and outputs when done.
		So, in this example, internally, it is -25 + 1 + 2 + 10 + 16 + 20.
	Input= [1, 2, 10, 16, 20] 
	Output = [24]
```