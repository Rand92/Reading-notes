# Expressions and operators

> Last modified: May 21, 2021

#### JavaScript has the following types of operators :

- Assignment operators
- Comparison operators
 - Arithmetic operators
- Bitwise operators
- Logical operators
- String operators
- Conditional (ternary) operator
- Comma operator
- Unary operators
- Relational operators

#### Operator precedence :

|**Operator type** | **Individual operators**| 
|------------  | ---------- |
| member	| . [] |
call / create instance|	() new
negation/increment	|! ~ - + ++ -- typeof void delete
multiply/divide | * / %
addition/subtraction |	+ -
bitwise shift |	<< >> >>>
relational |	< <= > >= in instanceof
equality	| == != === !==
bitwise-and |	&
bitwise-xor	| ^
bitwise-or	|
logical-and |	&&
logical-or	| ||
conditional |	?:
assignment	| = += -= *= /= %= <<= >>= >>>= &= ^= |= &&= ||= ??=
comma |	, 

### Expressions
An expression is any valid unit of code that resolves to a value.
Every syntactically valid expression resolves to some value but conceptually, there are two types of expressions: with side effects (for example: those that assign value to a variable) and those that in some sense evaluate and therefore resolve to a value.

JavaScript has the following expression categories:
- Arithmetic: evaluates to a number. (Generally uses [arithmetic operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#arithmetic_operators).)
- String: evaluates to a character string. (Generally uses [string operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#string_operators).)
- Logical: evaluates to true or false. (Often involves [logical operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#logical_operators).)
- Primary expressions: Basic keywords and general expressions in JavaScript.
- Left-hand-side expressions: Left values are the destination of an assignment.

# Loops and iteration

> Last modified: Mar 29, 2021

Loops offer a quick and easy way to do something repeatedly.
There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!)

The various loop mechanisms offer different ways to determine the start and end points of the loop. There are various situations that are more easily served by one type of loop over the others.

### The statements for loops provided in JavaScript are:

- for statement
- do...while statement
- while statement
- labeled statement
- break statement
- continue statement
- for...in statement
- for...of statement
 

**Full articles >>**
[loops and iterations](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration) , [Expressions and operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
