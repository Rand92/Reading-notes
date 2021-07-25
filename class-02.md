# TEXT IN HTML
When creating a web page, you add tags (known as markup) to the contents of the page. These tags provide extra meaning and allow browsers to show users the appropriate structure for the page.
- **Structural markup**: the elements that you can use to
describe both headings and paragraphs
- **Semantic markup** : which provides extra information; such as where emphasis is placed in a sentence, that something you have written is a quotation (and who said it), the meaning of acronyms, and so on .

### Headings :
HTML has six "levels" of headings:
[< h1 >] is used for main headings
[< h2 >] is used for subheadings
If there are further sections under the subheadings then the [< h3 >] element is used, and so on... 
### Paragraphs
To create a paragraph, surround the words that make up the paragraph with an opening [< p >] tag and closing [< /p >] tag. By default, a browser will show each paragraph on a new line with some space between it and any subsequent paragraphs.

### Visual Editors & Their Code views 
Content management systems and HTML editors such as *Dreamweaver* usually have two views of the page you are creating: a visual editor and a code view.
- **Visual editors** often resemble word processors. Although each editor will differ slightly, there are some features that are common to most editors that allow you to control the presentation of text.
- **Code views** show you the code
created by the visual editor so you can manually edit it, or so you can just enter new code yourself. It is often activated using a button with an icon that says HTML or has angled brackets. White space may be added to the code by the editor to make the code easier to read.
### Semantic Markup
There are some text elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages — they are known as semantic markup.
![semantic markup](https://miro.medium.com/max/1000/1*zHJFnu7QF-PgUb8108aLcA.png)

## Introducing CSS
**CSS** allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface.
**CSS** allows you to create rules that control the way that each individual box (and the contents of that box) is presented.
![HTML & CSS & JS](https://html-css-js.com/images/og.jpg)
**CSS** Properties Affect How El ements Are Displayed
**CSS** declarations sit inside curly brackets and each is made up of two parts: a *property* and a *value*, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon.
### CSS Selectors
There are many different types of CSS selector that allow you to target rules to specific elements in an HTML document.
### Why use External Style Sheets?
When building a website there are several advantages to placing your CSS rules in a separate style sheet. All of your web pages can share the same style sheet. This is achieved by using the  [< link >] element on each HTML page of your site to link to the same CSS document. This means that the same code does not need to be repeated in every page (which results in less code and smaller HTML pages).
### Different versi ons of CSS & Browser Quirks
CSS1 was released in 1996 and CSS2 followed two years later. Work on CSS3 has been ongoing but the major browsers have already started to implement it.Any seasoned user of CSS will tell you that some browsers display a few of the CSS properties in an unexpected way. But finding and squashing those bugs is easy when you know how...
## Basic Basic JavaScript Instructions
A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon.You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code. A script will have to temporarily store the bits of information it needs to do its job. It can store thisdata in variables.
![declaring variables](https://www.wikihow.com/images/thumb/c/c8/Declare-a-Variable-in-Javascript-Step-8.jpg/v4-460px-Declare-a-Variable-in-Javascript-Step-8.jpg)
### DATA TYPES
- NUMERIC DATA TYPE
- strings DATA TYPE
- Boolean DATA TYPE
### ARRAYS
An array is a special type of variable. It doesn't just store one value; it stores a list of values.
### EXPRESSIONS
An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions.
### OPERATORS
Expressions rely on things called operators; they allow programmers to create a single value from one or more values.
## Decisions and Loops
Scripts often need to behave differently depending upon how the user interacts with the web
page and/or the browser window itself. To determine which path to take, programmers often
rely upon the following three concepts:
- **EVALUATION** You can analyze values inyour scripts to determine whether or note they match expected results
- **DECISIONS** Using the results of evaluations, you can decide which path your script should go down
- **LOOPS** There are also manyoccasions where you will want to perform the same set of steps repeatedly
### USING COMPARISON OPERATORS
At the most basic level, you can evaluate two variables using a comparison operator to return a true or false value.
### USING LOGICAL AND
The logical AND is used to see if the user's score is greater than or equal to the pass mark in both of the rounds of the test. The result is stored in a variable called passBoth

