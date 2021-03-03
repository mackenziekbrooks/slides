---
author: Prof. Mackenzie Brooks, DH Librarian
title: ARTH 383 // markup + markdown
date: April 23, 2019
---

# Icebreaker
Earliest memory of the internet 

# Goals
* understand value of plain text
* create first website!
* become familiar with Markdown

# what is Digital Humanities? 

# what is DH? 
* remediation!
* print no longer primary medium 

# environment setup
1. Text editors: Sublime, Atom, Notepad
2. Browser other than Safari. 

# why plain text
* Because you're writing code, not a document.
* For computers first, then humans. 
* Content matters, not style. 

# activity 1 
1. Open your syllabus in Word. 
2. Save it as another file type (.xml, .rtf, .txt or others).
3. Open your new file in Sublime. What do you see? What is different? What is messed up? 

# markup

# Hypertext Markup Language

# HTML
* building block of the Web
* set of pre-defined tags/elements
* adds structure to a document/website
* tags define the piece of content within them 

# HTML
```
<!DOCTYPE html>
<html>
	<head>
		<title>Page Title</title>
	</head>
	<body>
		<h1>My First Heading</h1>
		<p>My first paragraph.</p>
	</body>
</html>
```

# your first website! 
1. Open Sublime and enter your HTML. 
2. Save the document as ```index.html``` to your Desktop.
3. In your browser, open your new file. What do you see? 

# activity 2
1. Using the [W3 Schools](https://www.w3schools.com/html/) as a reference, add three more HTML tags to your website. 
2. Can you figure out how to add a link to another website? An image? 

# Cascading Style Sheets
* different syntax than HTML
* list of rules, not a document
* usually lives in a separate file

# CSS
```
body {
    background-color: #d0e4fe;
}

h1 {
    color: orange;
    text-align: center;
}

p {
    font-family: "Times New Roman";
    font-size: 20px;
}
```
# getting started with CSS
1. Create a new text document called ```style.css```, saved to the same folder as your ```index.html```. 
2. Add your CSS. 
3. In your HTML doc, add the following line within the ```<head>``` tag: 
	```
	<link rel="stylesheet" type="text/css" href="style.css">
	```

# activity 3
1. Using the [W3 Schools](https://www.w3schools.com/css/default.asp) as a reference, add some more styles to your website.
2. Can you change the background color? Font?

# markdown 

# Markdown 
* A markup language designed to be lightweight and readable by humans.
* Easily transformed into HTML or other formats. 
* Used on the [Florence As It Was](https://raw.githubusercontent.com/florenceasitwas/site/master/_texts/paatz/orsanmichele_paatz_dau.md) website.  

# Markdown syntax
``` 
# Heading 1
## Heading 2
## Heading 3 

[Link text](URL)

* List item 1
* List item 2
* List item 3 

*italics*
**bold**
```
# activity 4
* Create a new text document in Sublime. Save it as ```index.md```. 
* Using the content of your website, recreate it in Markdown. 
* To check your work, paste into [Dillinger.io](https://dillinger.io/)




