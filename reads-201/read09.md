# Form
### Why Forms?
The best known form on the web is probably
the search box that sits right in the middle of
Google's home page addition to enabling users to
search, forms also allow users
to perform other functions
online. You will see forms
when registering as a member
of a website, when shopping
online, and when signing up for
newsletters or mailing lists.
### Form Controls
There are several types of form controls that
you can use to collect information from visitors
to your site.
### Summary
Whenever you want to c XX ollect information from
visitors you will need a form, which lives inside a
[< form >] element.
XX Information from a form is sent in name/value pairs.
XX Each form control is given a name, and the text the
user types in or the values of the options they select
are sent to the server.
XX HTML5 introduces new form elements which make it
easier for visitors to fill in forms.

# Lists, Tables and Forms
### Web Developer Toolbar
This helpful extension for Firefox and Chrome
provides tools to show you the CSS styles that
apply to an element when you hover over it,
along with the structure of the HTML.
- Outlines
When you hover over an
element, a red outline will be
drawn around it, showing you
how much space the element
takes up.
This tool also allows you to change the screen size, validate your HTML and CSS code, and turn off images.
- Structure
While you are hovering over
an element, the structure will
be shown at the top of the
window. Here you can see the
<li> element has a class of
completed, inside a <ul> with
a class called to-do. The list
is inside a <div> element with
an id of page, and this sits
inside the <body> and <html>
elements.
This can be very helpful when
writing CSS selectors to help you
target the right element.
- CSS styles
When hovering over an element,
click with your mouse to display
the CSS. You will be shown the
rules that apply to that element
(and the line they are on). Above
the rules, you can see the name
of the style sheet (and the path
to it).
This helps check which styles
are being applied to an element.
You can use it on code for your
own site or when you want to
see what styles someone else is
using on their site.

### Summary
** LISTS , TAB LES AND FORMS **
In addition to the CSS p XX roperties covered in other
chapters which work with the contents of all elements,
there are several others that are specifically used to
control the appearance of lists, tables, and forms.
XX List markers can be given different appearances
using the list-style-type and list-style image
properties.
XX Table cells can have different borders and spacing in
different browsers, but there are properties you can
use to control them and make them more consistent.
XX Forms are easier to use if the form controls are
vertically aligned using CSS.
XX Forms benefit from styles that make them feel more
interactive.
# Events
### DIFFERENT EVENT TYPES
Here is a selection of the events that occur in the browser while you are
browsing the web. Any of these events can be used to trigger a function
in your JavaScript code.
![events types](http://go.forrester.com/wp-content/uploads/2020/08/EB2954E5492440BC8B6FD4C488A08CDE.png)

## HOW EVENTS TRIGGER JAVASCRIPT CODE
When the user interacts with the HTML on a web page, there are three
steps involved in getting it to trigger some JavaScript code.
Together these steps are known as event handling.
1. Select t he element
node(s) you want the
script to respond to.
For example, if you want to
trigger a function when a user
clicks on a specific link, you need
to get the DOM node for that
link element. You do this using a
DOM query (see Chapter 5).
The UI events that relate to the
browser window (rather than the
HTML page loaded in it) work
with the window object rather
than an element node. Examples
include the events that occur
when a requested page has
f inished loading, or when the
user scrolls. You will learn about
using these on p272.
8 EVENTS
2. Indicate which event on
the selected node(s) will
trigger the response.
Programmers call this binding an
event to a DOM node.
The previous two pages showed
a selection of the popular events
that you can monitor for.
Some events work with most
element nodes, such as the
mouseover event, which is
triggered when the user rolls
over any element. Other events
only work with specific element
nodes, such as the submit event,
which only works with a form.
3. State the code you want
to run when the event
occurs.
When the event occurs, on a
specified element, it will trigger
a function. This may be a named
or an anonymous function.
## THREE WAYS TO BIND ANbEVENT TO AN ELEM ENT
Event handlers let you indicate which event you
are waiting for on any particular element.
There are three types of event handlers.
## THE EVENT OBJECT
### DIFFERENT TYPES OF EVENTS
In the rest of the chapter, you learn about the
different types of events you can respond to.
Events are defined in:
• The W3C DOM specification
• The HTMLS specification
• In Browser Object Models
