# HTML Syntax
html stands for " i dont rmember" and every document starts and ed wih the element   
`<html> </html>`
<h1..2..3.....6>
# Basic HTML elements
- Content elements: It starts with a `<element></element>`
- Void Elements: does not need a closing tag `<img>` examples of void elements are: area, base, br, col, command, embed, hr, img, input, keygen, link, meta, param, source, track, wbr.

## Font modifiers

### Comments
 Comments are important for describing the next line of code.
`<!-- Comments -->`

<!-- Comments -->
<p> paragraph </p>

The main element is used to represent the main content of the body of an HTML document. Content inside the main element should be unique to the document and should not be repeated in other parts of the document.

Example Code
<main>
  <h1>Most important content of the document</h1>
  <p>Some more important content...</p>
</main>

indentation is important in HTML5

image is a void element, void elements don't have a closing tag.

HTML attributes are special words used inside the opening tag of an element to control the element's behavior. The src attribute in an img element specifies the image's URL (where the image is located).
<img src="site url or local address">

all images should have an alt attribute and that is meant to imporve accesibility and is displayed when the image fails to load.

<img alt= "A cute orange cat lying on its back"src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg">

anchors are used to do hyperlinks to another sites. they will have a href attribute and the contents are text shown

<a href="https://freecatphotoapp.com">link to cat pictures</a>

You can turn any text into a link, such as the text inside of a p element.
 <p>See more <a href ="https://freecatphotoapp.com">cat photos</a> in our gallery.</p>

 the target attribute for anchors specifies where to open the linked document.
 target ="_blank" opens the linked doucment in a new tab or window.

 other types of elements such as images can also be turned into links by putting them into anchors.

 <a href="https://freecatphotoapp.com"> <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."> </a>

 SEO = Search Engine Optimization

Section element is used to define sections in a document (chapters, headers, footers) Helps with SEO and accesibility

 <section>
  <h2>Section Title</h2>
  <p>Section content...</p>
</section>

unordered lists
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>

Ordered lists work similarly but the element is <ol></ol>

You can nest elements such as image in figure elements

<figure>
  <img src="image.jpg" alt="A description of the image">
  <figcaption>A cute cat</figcaption>
</figure>

use em element for emphasis- basically italic
jeje<em>haha</em>
Use strong element for indicating importance or urgency- bascially bold

The form element is used to get information from a user like their name, email, and other details.
the attribute action tells the browser which direction should the data be sent to

action="/submit-url"

input is a void element too, and can be used to ask for info.

attributes are type name (placeholder is like a hint)

input and button are inline elements so they will show automatically on the same line

radio buttons for questions where you only want one answer out of multiple options.
---
# SMOL James Input
## Typography Tags/elements : Opening and Closing
### paragraph tag

`<p>hello world </p>`

### header tag
`<h1> Header </h1>`

## Utility Tags
### anchor tag
you can set a text or image to redirect you to another instance.
- ATTRIBUTES
- href = the address where the anchor is going to be redirected
- target = whether you want to open a another tab/window or redirect on the sam instance

`<a href = "any address" target= "_blank"> children content - shown on html document</a>`
### image tag
show an image in your document,
- ATTRIBUTES
- src = the image's address
- alt = default text when the image is not found or could not be loaded.
`<img src="image address" alt="default text">`

### input tag
it opens a textbox where user is prompted to enter info, it is of good syntax to put them inside a label tag
- ATTRIBUTES
- placeholder = default text shown to the user
`<label><input placeholder="Prompt the user"></label>`

### button tag
Shows a button on screen and you can add functionlaity. you can put a paragraph tag inside the button tag to add text to the button.

## Container Tags
- Container tags are utilized for styling leveraging on the division.
### division tag
generic divider container
`<div></div>`
### form tag
wraps section of user input.it adds semantic meaning to your input tags
`<form> </form>`
### section tag
greater division, they are more useful when adding styles. SImilar to a page break

## NOTE:
By typing ! in the index.html file it can launch the visual studio to boil a plate of code

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
## Head Tag
It will work as Search engine optimization, and will have the meta information of the file.

```
<header> </header>
  <h1> </h1>
  <nav>
    <a href="#footer">
      <p>Footer</p>
    </a>
   </nav>
   <main> </main>
<footer id="footer"></footer>
```
## Style atribute
```
<img style ="width>

