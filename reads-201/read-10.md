# Error Handling & Debugging
### ORDER OF EXECUTION
To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run:
This script above creates a greeting message, then
writes it to an alert box (see right-hand page). In
order to create that greeting, two functions are used:
greetUser () and getName () .
You might think that the order of execution (the
order in which statements are processed) would be
as numbered: one through to four. However, it is a
little more complicated.
### EXECUT.ION CONTEXTS
The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope.
EXECUTION CONTEXT
JavaScript
Hello Molly
Every statement in a script lives in one of three
execution contexts:
Q GLOBAL CONTEXT
Code that is in the script, but not in a function.
There is only one global context in any page.
FUNCTION CONTEXT
Code that is being run within a function.
Each function has its own function context.
Q EVAL CONTEXT (NOT SHOWN)
Text is
## EXECUTION CONTEXT& HOISTING
Each time a script enters a new execution context, there are two phases
of activity:
- 1: PREPARE
• The new scope is created
• Variables, functions, and arguments are created
• The value of the this keyword is determined
- 2: EXECUTE
• Now it can assign values to variables
• Reference functions and run their code
• Execute statements
## UNDERSTANDING SCOPE
In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object.
## A DEBUGGING WORKFLOW
Debugging is about deduction: eliminating potential causes of an error.
Here is a workflow for techniques you will meet over the next 20 pages.
Try to narrow down where the problem might be, then look for clues


![tips](https://images.slideplayer.com/26/8537467/slides/slide_3.jpg)