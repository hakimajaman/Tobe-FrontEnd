# Lesson 1

## Introduction to HTML

* What is HTML? [wiki](https://en.wikipedia.org/wiki/HTML)

### Prerequisites

What things do you need to install for programming an HTML?  

* Web Browser
* Text Editor ( Vim, VS-Code, Sublime, Notepad(Not Recommended), Gedit(Not Recommended) )

## Getting Started

We need a .html file for start code the HTML and in this section, we will show the picture, so, we need to have a .jpg or .png file.

### View the .html file (Introduction to Tag)

```<html>``` this is a tag

All of HTML is started with ```<html>``` and closed with ```</html>```

Tag is ```<>```, and endTag is ```</>```  

if you open the tag, you need to close it after that.  
some tag is doesn't need to use an open and then close tag, like ```<input>``` tag. it only needs to use one tag (without open and without close), so, it will be written like this ```<input/>```  

if you using 2 tags, your text will be in the middle of the tags, like this. ```<h1>This is your text<h1/>```.  
if you using 1 tag, your text will be in the tag, but, it have some rule, like this. ```<input value="this is your text"/>```

```<!DOCTYPE html>``` this is not a tag, it just tells your web browser that you using a version of html5, and it is always to be the first before of the HTML tag

```<head></head>```
next, we have ```<head>``` tag.  
this tag is for your web browser tab bar.

```<meta />```  
next, we have ```<meta />``` tag.  
this provides metadata about the HTML document, it will not be displayed on the page but will be machine parsable. [more about meta](https://www.w3schools.com/tags/tag_meta.asp)  
charset  

in ```meta``` tag, that has 3 variables:
* charset => for the characters encoding to your web browser, [UTF-8 Ex](https://www.w3schools.com/html/html_charset.asp)
* name => A <meta> viewport element gives the browser instructions on how to control the page's dimensions and scaling
* content => set content size, [more about](https://www.w3schools.com/tags/tag_meta.asp)

```<body>```  
next, we have ```<body></body>``` tag.
all your code, will be in this tag.

```<a></a>```  
next, we have **<a>** tag.  
If you want to put a link, you can put it in this tag ```<a href="www.google.com"> Google </a>```.

```<h1></h1> or <h2></h2> or <h3></h3>```  
next, we have ```<h1>``` tag.
# this is Heading Text 1.
## this is Heading Text 2.
### this is Heading Text 3.

