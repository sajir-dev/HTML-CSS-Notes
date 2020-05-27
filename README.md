# HTML-CSS-Notes

## 01-HTML Introduction

**HTML** - Hyper Text Markup Language <br>
**CSS** - Cascading Styilng Sheet <br>

**head *tag*** - None of the items inside head tag is not rendered in a webpage <br>

*title* - title of the website, appears on the browser tab <br>

Live server plugin can be used with VS Code for local dev environment <br>

## 02- HTML Tags

**strong** - bold <br>
**em** - italic <br>
**small** - make the font small <br>
**h1,h2,h3,h4,h5,h6** -  Heading tags based on size and importance<br>
**ul** - unordered list- actaully wraps *li* tags <br>
**li** - list items <br>
**ol** - list items will be numbered rather than dots in *ul* <br>
**div** - used to group html elements - semantic tags after HTML5 can be replaced this tag<br>
**span** - used to hook-up styling or functioning of a particular portion. <br>
**br** - breaks the line <br>
**img** - image tag <br>
**src** - provides path of the file <br>
**alt** - used for screen readers <br>
**a** - anchor tag <br>
**blockquote** - text is a tab space away (intends) from the screen, used to mention quotation <br>
**cite** - attribute tag for a blockquote <br>
**style** - add styling to an element <br>
**<!--comments out--!>** - ctrl+/ to un/commment out a block<br><br>


## 03 - HTML Web Forms
**form** - creates a form<br>
**action** - posts form data to a server<br>
**type** - input type, can be text, number, date, email, password etc.. used for frontend check up of 
input for providing proper keyboard<br>
**id** - id's used to hook up data in JavaScript or to put styling in css <br>
**label** -  to label the input with id <br>
**label for= *id* ** - to label particular field <br>
**input type="radio"** - radio button <br>
*input type="radio" name="gender" value="male"* <br>
*input type="radio" name="gender" value="female"*<br>
Just one of the above radio button can be selected because they have common name.
To select multiple radio button give them different names.<br>
*value* - helps to understand the server which value is selected<br>
**select** - dropdown<br>
**option** - to put options for the drop down<br>
**value** - to identify the input field for the server <br>
**textarea** - field for text input in an area <br>
**input type="submit"** - for submitting the form value <br>
**required** - used to define not empty fields <br>

## 04-CSS Introduction

syntax: <br>
*selectors { <br>
    property1 :value1; <br>
    property2 :value2; <br>
    etc.. <br>
}* <br>

Creating an external stylesheet can keep the whole styling at one place for all the pages and it will be easier for future updates. <br>

**link** *link rel="stylesheet" href="path/filename.css"* <br>

border-width: 3px;<br>
border-style: solid;<br>
border-color: steelblue;<br>
can be re written as border: 3px solid steelblue <br>

text-shadow: horizontal vertical color <br>

inline elements:span. strong, a, etc..<br>
block level elements: takes full width of the page.<br>
Eg: p, h1, div, etc...<br>
Margin and Padding for block level elements covers whole side of the block<br>
For inline elements margin is applied only on left and right<br>
Padding in an inline element can overlap in vertical direction <br>
Margin in a block-level element overlaps in vertical direction <br>

*inline-block* can be used to avoid padding and margin overlaps
<br>

**user agent stylesheet** browser defined style of default styles
<br>

## 05-Classes and Selectors
syntax: *.classname { <br>
    property : value; <br>
} <br>

class can be applied to group and style elements, eg: CTA Button<br>

*div.class* - selects div with a class attached to it. ie; selects div class="class"   (also called descendent selector)<br>

*div. class* - selects a class inside parent element div. ie; selects div
..p class="class"..</div> <br>
opening and closing brackets are omitted.<br>

a[href="part-in-the-filename"] can be used as a selector for a tags. For eg: a tags that has google in them, or a file name with extension pdf, etc...
<br><br>

Cascade- priority for last defined style.
<br><br>

Not all properties are inheritted, to make them inherit add the property *inherit* with child <br>

## 06-HTML5 Semantic Tags

*main*- for the main content of the webpage <br>
*section*- defines a certin section of a webpage<br>
*article*- defines an article or blog <br>
*aside*- aside content<br>
*header* *footer* exactly as it is <br>
<br>
Learn more about semantics at: <br>
https://www.w3schools.com/html/html5_semantic_elements.asp
<br><br>
 
 ## 08-CSS Layout and Positioning

*static*
*relative*
*fixed*
*absolute*
*sticky*


## 09-Pseudo classes

*hover*
*focus*
*first-child*

read more at https://www.youtube.com/redirect?v=FMu2cKWD90g&event=video_description&redir_token=17QSe-Awy2h6uAD9FRqRTU-1JLB8MTU5MDY3NTk1M0AxNTkwNTg5NTUz&q=https%3A%2F%2Fwww.w3schools.com%2Fcss%2Fcss_pseudo_elements.asp

## 09-Responsive web and media queries
Media qeuries: Tell the browser how to style an elment at a particular view port<br>
Viewport meta tag: 

