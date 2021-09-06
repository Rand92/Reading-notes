# Passing Functions as Props

### Lists and Keys
First, let’s review how you transform lists in JavaScript.

### How to Use the Spread Operator (…) in JavaScript
What is the spread operator?
InJavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.
“When ...arr is used in the function call, it ‘expands’ an iterable object arr into the list of arguments.” — JavaScript.info
The spread operator was added to JavaScript in ES6 (ES2015), just like the rest parameters, which have the same syntax: three magic dots ….

What is ... used for?
“Spread operator to the rescue! It looks similar to rest parameters, also using ..., but does quite the opposite.” — JavaScript.info
Take trying to find the largest number in an array with Math.max():
What else can … do?
The … spread operator is useful for many different routine tasks in JavaScript, including the following:
1. Copying an array
2. Concatenating or combining arrays
3. Using Math functions
4. Using an array as arguments
5. Adding an item to a list
6. Adding to state in React
7. Combining objects
8. Converting NodeList to an array
In each case, the spread syntax expands an iterable object, usually an array, though it can be used on any interable, including a string.