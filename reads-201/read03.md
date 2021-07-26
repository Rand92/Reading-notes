# Lists 
**Ordered Lists**
There are lots of occasions when we
need to use lists. HTML provides us with
three different types:
- Ordered lists are lists where each item in the list is
numbered. For example, the list might be a set of steps for
a recipe that must be performed in order, or a legal contract
where each point needs to be identified by a section
number.
- Unordered lists are lists that begin with a bullet point
(rather than characters that indicate order).
- Definition lists are made up of a set of terms along with the
definitions for each of those terms.
**Summary**
There are three types of HTML lists: ordered,
unordered, and definition.
 Ordered lists use numbers.
*Unordered lists use bullets.*
*Definition lists are used to define terminology.*
*Lists can be nested inside one another.*
![lists](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/07/html-lists-df.jpg)
# Boxes 
At the beginning of this section on CSS,
you saw how CSS treats each HTML
element as if it lives in its own box.
## Box Dimensions 
[ width, height] 
By default a box is sized just big
enough to hold its contents. To
set your own dimensions for a
box you can use the height and
width properties.
The most popular ways to
specify the size of a box are
to use pixels, percentages, or
ems. Traditionally, pixels have
been the most popular method
because they allow designers to
accurately control their size.
When you use percentages,
the size of the box is relative to
the size of the browser window
or, if the box is encased within
another box, it is a percentage of
the size of the containing box.
## Limiting Width
[min-width, max-width]
Some page designs expand and
shrink to fit the size of the user's
screen. In such designs, the
min-width property specifies
the smallest size a box can be
displayed at when the browser
window is narrow, and the
max-width property indicates
the maximum width a box can
stretch to when the browser
window is wide.
These are very helpful properties
to ensure that the content of
pages are legible (especially on
the smaller screens of handheld
devices). For example, you can
use the max-width property to
ensure that lines of text do not
appear too wide within a big
browser window and you can
use the min-width property
to make sure that they do not
appear too narrow.
## Limiting Height 
[min-height, max-height]
In the same way that you might
want to limit the width of a box
on a page, you may also want
to limit the height of it. This is
achieved using the min-height
and max-height properties.
## overflowing Content 
[overflow]
The overflow property tells the
browser what to do if the content
contained within a box is larger
than the box itself. It can have
one of two values:
- hidden
This property simply hides any
extra content that does not fit in
the box.
- scroll
This property adds a scrollbar to
the box so that users can scroll
to see the missing content.
## Border, Margin & Padding
Every box has three available properties that
can be adjusted to control its appearance:
Border, Ma rgin
& Padd ing
- 1 :Border
Every box has a border (even if
it is not visible or is specified to
be 0 pixels wide). The border
separates the edge of one box
from another.
- 2 :Margin
Margins sit outside the edge
of the border. You can set the
width of a margin to create a
gap between the borders of two
adjacent boxes.
- 3 :Padding
Padding is the space between
the border of a box and any
content contained within it.
Adding padding can increase the
readability of its contents.
## White space & Vertical Margin
The padding and
margin properties
are very helpful
in adding space
between various
items on the page.
## padding
The padding property allows
you to specify how much space
should appear between the
content of an element and its
border.
The value of this property is
most often specified in pixels
(although it is also possible to
use percentages or ems). If a
percentage is used, the padding
is a percentage of the browser
window (or of the containing box
if it is inside another box).
## Margin
The margin property controls
the gap between boxes. Its value
is commonly given in pixels,
although you may also use
percentages or ems.
If one box sits on top of another,
margins are collapsed , which
means the larger of the two
margins will be used and the
smaller will be disregarded.
## Hiding Boxes visibility
The visibility property allows
you to hide boxes from users
but It leaves a space where the
element would have been.
This property can take two
values:
- **hidden**
This hides the element.
- **visible**
This shows the element.
### Summary
CSS treats each HTML e XX lement as if it has its own box.
- You can use CSS to control the dimensions of a box.
- You can also control the borders, margin and padding
for each box with CSS.
- It is possible to hide elements using the display and
visibility properties.
- Block-level boxes can be made into inline boxes, and
inline boxes made into block-level boxes.
- Legibility can be improved by controlling the width of
boxes containing text and the leading.
- CSS3 has introduced the ability to create image
borders and rounded borders.
# ARRAYS
An array is a special type of variable. It doesn't
just store one value; it stores a list of values.
## CREATING AN ARRAY
You create an array and give it
a name just like you would any
other variable (using the var
keyword followed by the name of
the array).
The values are assigned to the
array inside a pair of square
brackets, and each value is
separated by a comma. The
values in the array do not need
to be the same data type, so you
can store a string, a number and
a Boolean all in the same array
## VALUES IN ARRAYS
Values in an array are accessed as if they are in
a numbered list. It is important to know that the
numbering of this list starts at zero (not one).
# USING IF ... ELSE STATEMENTS
Here you can see that an
if ... e 1 se statement al lows you
to provide two sets of code:
1. one set if the condition
evaluates to true
2. another set if the condition is
false
## USING SWITCH STATEMENTS
In this example, the purpose
of the switch statement is to
present the user with a different
message depending on which
level they are at. The message is
stored in a variable called msg.
The variable called l eve 1
contains a number indicating
which level the user is on. This
is then used as the switch value.
(The switch value could also be
an expression.)
## KEY LOOP CONCEPTS
- **KEYWORDS**
You will commonly see these
two keywords used with loops:
- **break**
This keyword causes the
termination of the loop and tells
the interpreter to go onto the
next statement of code outside
of the loop. (You may also see it
used in functions.)
- **continue**
This keyword te lls the interpreter
to continue with the current
iteration, and then check the
condition again. (If it is true, the
code runs again.)
8 DECISIONS & LOOPS
- **LOOPS & ARRAYS**
Loops are very helpful when
dealing with arrays if you want to
run the same code for each item
in the array.
- **PERFORMANCE ISSUES**
It is important to remember
that when a browser comes
across JavaScript, it will stop
doing anything else until it has
processed that script.
If your loop is dealing with only
a small number of items, this
will not be an issue. If, however,
your loop contains a lot of items,
it can make the page slower to
load.
![while loop](https://cdn.educba.com/academy/wp-content/uploads/2019/11/Do-While-Loop-in-JavaScript-main.png)
