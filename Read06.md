# CSS *(Cascading Style Sheets)* 
 CSS allows you to create great-looking web pages. It is a language for specifying how documents are presented to users — how they are styled, laid out, etc.
A document is usually a text file structured using a markup language — HTML is the most common markup language, but you may also come across other markup languages such as SVG or XML.
Presenting a document to a user means converting it into a form usable by your audience. Browsers, like Firefox, Chrome, or Edge , are designed to present documents visually, for example, on a computer screen, projector or printer.

**CSS syntax**
CSS is a rule-based language — you define rules specifying groups of styles that should be applied to particular elements or groups of elements on your web page. For example "I want the main heading on my page to be shown as large red text."

**CSS Modules**
As there are so many things that you could style using CSS, the language is broken down into modules. You'll see reference to these modules as you explore MDN and many of the documentation pages are organized around a particular module. For example, you could take a look at the MDN reference to the Backgrounds and Borders module to find out what its purpose is, and what different properties and other features it contains. You will also find links to the CSS Specification that defines the technology (see below).
At this stage you don't need to worry too much about how CSS is structured, however it can make it easier to find information if, for example, you are aware that a certain property is likely to be found among other similar things and are therefore probably in the same specification. 
For a specific example, let's go back to the Backgrounds and Borders module — you might think that it makes logical sense for the background-color and border-color properties to be defined in this module. And you'd be right.

**CSS Specifications**
All web standards technologies (HTML, CSS, JavaScript, etc.) are defined in giant documents called specifications (or "specs"), which are published by standards organizations (such as the W3C, WHATWG, ECMA, or Khronos) and define precisely how those technologies are supposed to behave.

CSS is no different — it is developed by a group within the W3C called the [CSS Working Group}(https://www.w3.org/Style/CSS/).
## How To Add CSS
here are three ways of inserting a style sheet:
- External CSS
- Internal CSS
- Inline CSS

**External CSS**
With an external style sheet, you can change the look of an entire website by changing just one file!
Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.
**Internal CSS**
An internal style sheet may be used if one single HTML page has a unique style.
The internal style is defined inside the <style> element, inside the head section.
**Inline CSS**
  An inline style may be used to apply a unique style for a single element.
To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

 **CSS color Property**
  Colors play a vital role in making a web page usable or not. In CSS, we can control the foreground and background color of an element with the color and background properties. When I learned CSS back in the years, there wasn’t a straightforward guide or way to learn how to use colors in CSS.
**CSS color Property**
  
 | **Value**	| **Description** |
  ------| -----
color	| Specifies the text color. Look at CSS Color Values for a complete list of possible color values.	
initial	| Sets this property to its default value. Read about initial	
inherit	| Inherits this property from its parent element. Read about inherit

> *References* >> [What is CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS),  [ How To Add CSS](https://www.w3schools.com/css/css_howto.asp), [ CSS color](https://www.w3schools.com/cssref/pr_text_color.asp) 

