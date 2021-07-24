
# HTML & CSS
*Design and Build Websites*
> by Jon Duckett

You can download all of the code for this book online at: [htmlandcssbook](http://www.htmlandcssbook.com/code/)

### The Structure of This Book :
- HTML
- CSS
- Practical 

#### The different ways in which people access the web
and clarify some terminology are:
- **Browsers** : People access websites using
software called a web browser.
Popular examples include
Firefox, Internet Explorer, Safari,
Chrome, and Opera.
- **Web Servers**: When you ask your browser for
a web page, the request is sent
across the Internet to a special
computer known as a web
server which hosts the website.
- **Devices**: People are accessing websites
on an increasing range of devices
including desktop computers,
laptops, tablets, and mobile
phones. It is important to
remember that various devices
have different screen sizes and
some have faster connections to
the web than others.
- **Screen readers**: Screen readers are programs
that read out the contents of a
computer screen to a user. They
are commonly used by people
with visual impairments.

**How Websites Are Created?**
All websites use HTML and CSS, but content
management systems, blogging software, and
e-commerce platforms often add a few more
technologies into the mix.
When you visit a website, the web server
hosting that site could be anywhere in the
world. In order for you to find the location of
the web server, your browser will first connect
to a Domain Name System (DNS) server.
![how the web works](https://davidrbrown.com/wp-content/uploads/2011/03/internet.gif)

**HTML Uses Elements to Describe the Structure of Pages**
In the browser window you can see a web page that features exactly the same content as the Word document you met on the page 18. To describe the structure of a web page, we add code to the words we want to appear on the page.

**The Evolution of HTML**
Since the web was first created, there have been several different versions of HTML.
- HTML 4 Released 1997
- XHTML 1.0 Released 2000
- HTML 5 Released 2000

**DOCTYPEs**
Because there have been several versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using (although browsers usually display the page even if it is not included).
## CSS 
CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface.
![example](https://user-images.githubusercontent.com/432915/36014488-e3be47c4-0d1e-11e8-88b1-2aaccf69ec12.png)

You can specify the dimensions o XX f images using CSS.This is very helpful when you use the same sized images on several pages of your site.
![example2](https://www.thoughtco.com/thmb/Kx5Ob1o7R4s8yvblBqJC3hw18z8=/963x678/filters:no_upscale():max_bytes(150000):strip_icc()/css-background-100-example-3acfb4a7de454a699b82b30a8b056e6e.jpg)

**Traditional HTML Layouts**
HTML5 introduces a new set of elements that allow you to divide up the parts of a page. The names of these elements indicate the kind of content you will find in them. They are still subject to change, but that has not stopped many web page authors using them already.
![HTML Layouts](https://www.w3schools.com/html/img_sem_elements.gif)

# JAVASCRIPT & JQUERY
Interactive Front-End Web Development
> by JON DUCKETT

**EXAMPLES OF JAVASCRIPT IN THE BROWSER**
Being able to change the content of an HTML page while it is loaded in the browser is very powerful. 
- SLIDESHOWS : Slideshows can display a number of different images (or other HTML content) within the same space on a given page. They can play automatically as a sequence, or users can click through the slides manually. They allow more content to be displayed within a limited amount of space.
- FORMS : Validating forms (checking whether they have been filled in correctly) is important when information is supplied by users. JavaScript lets you alert the user if mistakes have been made. It can also perform sophisticated calculations based on any data entered and reveal the results to the user.

**Before you learn how to read and write the JavaScript
language itself, you need to become familiar with some key
concepts in computer programming**. They will be covered in
three sections:
- **A** : What is a script and how do I create one? 
[A script is a series of instructions that a computer can follow to achieve a goal.To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.]
- **B** : How do computers fit in with the world around them? [COMPUTERS CREATE MODELS OF THE WORLD USING DATA.
*OBJECTS* (THINGS) In computer programming, each physica l thing in the world can be represented as an object. 
Each object can have its own:
• Properties
• Events
• Methods
*Events* : There are common ways in which people interact
with each type of object. For example, in a car a
driver will typically use at least two pedals. The car
has been designed to respond differently when the
driver interacts with each of the different pedals:
• The accelerator makes the car go faster
• The brake slows it down 
, Similarly, programs are designed to do different things when users interact with the computer in different ways. For example, clicking on a contact link on a web page could bring up a contact form, and entering text into a search box may automatically trigger the search functionality.]
- **C** : How do I write a script for a web page?
[It is best to keep JavaScript code in its own JavaScript file. JavaScript files are text files (like HTML pages and CSS style sheets), but they have the . j s extension. The HTML <script> element is used in HTML pages to tell the browser to load the JavaScript file (rather like the <link> element can be used to load a CSS file). If you view the source code of the page in the browser, the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created.]