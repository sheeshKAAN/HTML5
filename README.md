Greetings, before starting the lessons, I would like to give you some information about the web.But before that, there are a few things I want to tell you.
You cannot learn software by just reading and watching, this is true for all programming languages ​​and many other things. You must put into practice what you have learned, and understand what is useful for what purpose. If you really want to learn, follow me on this journey and do the necessary things. Have fun everyone here😁
# Web Software
Web software is software used to add features to the HTML markup language that forms the basis of websites. Thanks to this software, websites can update themselves automatically without the need for a person to edit them.

There are no restrictions in web software; you can make any project you have in mind concrete by making the necessary preparations. The main factor here is that web software is not created in a single language. Web software is developed using many languages ​​such as **Javascript**, **HTML**, **CSS**, **Python**, **PHP**. The important thing here is which language will best meet your needs. This selection is made by professionals and they do the planning and coding.

# Key Components of Web Content
-  **Frontend:**
  
Frontend is the surface layer of the web application that users directly interact with and can see visually. Technologies such as HTML, CSS and JavaScript are used in the frontend development process.
-  **Backend:**
  
The backend is managed throughout the web server and is the part that users cannot see. The backend contains transfers such as database data and server-side programming. Technologies used in the backend development process include languages ​​such as PHP, Python, Ruby and Java.
-  **Database:**
  
The he database allows storing and managing data used in web applications. There are two main types of databases: SQL and NoSQL. These types include popular database systems such as MySQL, PostgreSQL, MongoDB and Couchbase.
# Web
Web software offers significant value to businesses and users today. Developing web applications can be accomplished successfully by understanding the basic components and development processes and choosing the right approaches. Developers' and project managers' planning and implementation of web software projects by taking these processes and approaches into consideration will help improve the quality, performance and user satisfaction of the application.

Yes, after briefly summarizing the web part, we can now get into HTML.

# What is HTML?
HTML **(Hypertext Markup Language)** is a markup language used when creating web pages, it forms the basis of the web page. CSS, which makes it look more beautiful and organized, is JavaScript, which allows it to be used in a more dynamic structure. HTML5 is the fifth version of the HTML markup standard, one of the core technologies of the Internet.

# Basis Elements
- ```<!DOCTYPE>``` : It is used to determine which version of HTML should be interpreted when interpreting the HTML page. All HTML pages begin with the ```<!DOCTYPE>``` definition. This definition represents the HTML version of the page.
  
- ```<html>``` : It is the most basic tag of HTML and covers all other tags, that is, all other HTML tags must be written within the ```<html>``` tag.
 
- The ```<head>``` tag contains header information about the page. In other words, it contains information that the user cannot see when he enters a web page, but will be loaded in the background and continue functioning.
 
- ```<title>``` : tag is used to determine the ```<title>``` of the page and is located within the ```<head>``` tag.
 
- The ```<meta>``` tag is used to specify headers on web pages.

- ```<body>``` : tag contains all the text and tags that will appear. So, when a web page is opened, the contents of the ```<body>``` are displayed to the end user.
 
- ```<p>``` : this tag allows us to create paragraphs on the web page.
 
- ```<h1>```: This tag used for headings is ```<h1> <h2>, <h3>``` etc. It can be numbered as follows, and as the number increases, the size of the text decreases. The numbers are between ```<h1>``` and ```<h6>```.

# Tag Structure in HTML
Tags are used when marking texts in HTML. And when defining tags, the tag name is written inside ```< less than and >``` greater than signs.
That is, they are defined as ```<tagName>```. Additionally, opened tags are closed in the same way with **/** at the beginning.
That is, it is defined as ```<tagName> .. </tagName>```. However, this rule does not apply to all tags; some tags are closed by themselves, so you do not need to close them.
You will understand and learn their distinction better in the following lessons, but to give a few examples of tags that cannot be closed, ```<img> <br> <hr> <meta>``` etc. we can say

**Examples:**
```html
<p> paragraph </p>
```
```html
<h1> big title </h1>
```
```html
<title> ... </title>
```
# Attribute Structure in HTML
After creating the tags, it is necessary to examine the use of the attributes that make up the tags. You can think of attributes as the directives of tags. In other words, we define certain attributes to make the tag more functional. After opening the tag, we define the attribute as **key="value"**.

**Example:**
```html
<meta charset="UTF-8">
```
This example is both a self-closing label type and a combined label example, with the character set as the key and the UTF-8 value as the value. While some existing keys and values ​​represent certain things, some existing values ​​may be in an expression that you specify.

**Example:**
```html
<meta content="description" content="explanation...">
```
# Links in HTML
The <a> tag is used to link to an address in HTML. In this example, the href link is used to determine the address to go to when clicked. Attributes are used to specify more information about HTML tags.

**Example:**
```html
<a href="https://venge.io/">Venge</a>
```
# Image in HTML
The <img> tag is used to display images in HTML. If you remember, we mentioned that some tags close on their own, this tag is an example of them. Without attributes, the ```<img>``` tag won't display anything. In the ```<img>``` tag, **src=" "** is used to determine the image path, **alt=" "** is used for the alternative text that will appear if there is no image, **width=" "** and **height=" "** are used to adjust the width and height, and **title=" "** is used to create a description when hovered over.

**Example:**
```html
<img src="test.png" alt="Displayed when there is no picture." title="It only appears when you hover over this title." width="300" height="200">
```
# Listing in HTML
In HTML, lists are located within ```<li>``` between ```<ul>``` and ```<ol>``` tags.

**Example:**
```html
<ul>
    <li>apple</li>
    <li>pear</li>
    <li>plum</li>
</ul>
```
# Tags in HTML
Tags form the basis of HTML. Tags are predefined parts that we use when marking texts. So you cannot define a label yourself.

**Example:**
```html
<h1> ... </h1>
```
In some tags, we do not have to close the tags because they are self-closing tags. The structure of these tags is as follows;

**Example:**
```html
<img .../>
```
Now let's define a real tag and see its usage.
```html
<p> this is a paragraph tag </p>
```
The ```<p>``` tag is the tag used to mark paragraphs. You can enclose long and short texts in the ```<p>``` tag. Except for a few tags in HTML, tags are useless. In other words, they must be used in a qualified manner. What is quality? We will come to this topic in the next lesson.

**Example:**
```html
<a href="https://venge.io/">venge</a>
```
We used the linking tag here. So, when the prototurk text is clicked, we created a link that will go to prototurk.com. And using the ```<a>``` tag without qualifications here will not yield any results. In other words, we use attributes, as in this example, to make certain directives. Here href is the attribute of this tag and takes the address of the link to be navigated as value.
# Attributes in HTML
**One important thing in HTML is attributes**. Qualifiers are the parts used inside the labels and serve to fulfill the label's instructions. Attributes are generally used as ```attribute="value"```, but in some cases you may also see attributes without a value. Attribute values ​​must always be written in quotes.

**Example:**
```html
<label attribute1="value" attribute2="value"></label>
```
As you can see, they are defined as attribute="value". And a tag can take more than one attribute. Now let's examine it through a real example.

**Example:**
```html
<img src="test.png">
```
Here, the ```<img>``` tag means nothing without the src attribute. By specifying the path of the image with src, we make it appear on the screen. For this reason, you can always consider tags and attributes.
# Text Formatting Tags in HTML
HTML has certain tags to format expressions, that is, to add new styles to them. List of them;

```<b>``` - Bold text

```<strong>``` - Important article

```<i>``` - Italic text

```<em>``` - Highlighted text

```<mark>``` - Marked text (While reading books, we would underline an important part with a yellow pen, this is exactly it ^^)

```<small>``` - Small text (Even if written in capital letters, it appears smaller than normal text)

```<del>``` - Deleted text (Don't ask what the deleted text does, for example, when the price of the product changes, they cross it out and write the new price, this is in that logic)

```<ins>``` - Inserted text

```<sub>``` - Subscript text

```<sup>``` - Superscript text

Pretty simple right? :D 

**Examples:**
```html
<p>
    This is <b>bold</b> text and this is <strong>important bold text.</strong> <br>
    This is <i>italic text</i> and this is <em>emphasized text.</em> <br>
    This is <mark>marked text</mark>, this is <small>SMALLUM</small> TEXT. <br>
    This is now <del>deleted</del> and this is <ins>newly added</ins> text example :) <br>
    And finally, examples of the subscript H<sub>2</sub>O and m<sup>2</sup> can be given.
</p>
```
Let's give more detailed information about these.
# b and strong Tags 
It thickens when visible on both labels. The difference between each other is that the ```<b>``` tag's markup only makes it bold, while the ```<strong>``` tag's markup both makes it bold and indicates that the text is an important text when interpreted by the browsers.

**Example:**
```html
<b>Hello KAAN</b>
<strong>Have are you?</strong>
```
# i and em Tags
It is used for the slope of the text in both labels. The difference between them is that marking the ```<i>``` tag only shows italics, while marking the ``<em>``` tag both shows italics and indicates that that text is highlighted when interpreted by browsers.

**Example:**
```html
<i>italic writing</i>
<em>eat, work, run, dance</em>
```