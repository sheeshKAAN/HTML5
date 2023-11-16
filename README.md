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
![Screenshot_2023-11-16-00-13-17-845-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/f7dcff37-fd32-4f69-b1b2-e07d6b504eac)

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
![Screenshot_2023-11-16-00-15-25-167-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/8ced6e1e-5417-4cf1-bff9-ffc23f7a5d1c)

Let's give more detailed information about these.
# b and strong Tags 
It thickens when visible on both labels. The difference between each other is that the ```<b>``` tag's markup only makes it bold, while the ```<strong>``` tag's markup both makes it bold and indicates that the text is an important text when interpreted by the browsers.

**Example:**
```html
<b>Hello KAAN</b>
<strong>Have are you?</strong>
```
# i and em Tags
It is used for the slope of the text in both labels. The difference between them is that marking the ```<i>``` tag only shows italics, while marking the ```<em>``` tag both shows italics and indicates that that text is highlighted when interpreted by browsers.

**Example:**
```html
<i>italic writing</i>
<em>eat, work, run, dance</em>
```
# small Tag 
The ```<small>``` tag is used to make text smaller than it appears. Even if the text is written in capital letters, the text in this label appears smaller than the other letters.

**Example:**
```html
Can <small>this text appear smaller</small> when these texts are normal?
![Screenshot_2023-11-16-00-17-01-335-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/1490eda6-50c3-496f-8443-9232d655b0f4)
```
# mark Tag
We use the ```<mark>``` tag in HTML to draw and highlight the text with a yellow pen.

**Example:**
```html
this text is normal<mark>this text is crossed out in yellow</mark>
```
![Screenshot_2023-11-16-00-17-35-530-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/24d768ee-f903-48d0-9d41-c4eea683da4a)
# del Tag
We mark the strikethrough text with the ```<del>``` tag.

**Example:**
```html
Lemonade price <del> 1$ </del> 5$
```
![Screenshot_2023-11-16-00-18-01-805-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/863779a8-b705-48fe-827d-3ee34fc7b2fd)
# ins Tag
The ```<ins>``` tag is used when adding new posts to deleted posts using ```<del>```.

**Example:**
```html
Lemonade price <del> 1$ </del> <ins> 5$ </ins>
```
![Screenshot_2023-11-16-00-18-34-773-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/0ddeebe3-21b7-49b4-b8f0-80632ab2e8a3)
# sub Tag 
This tag is used to designate the text as a subscript. For example, when we say H2O, it would be correct to use the value 2 as a subscript.

**Example:**
```html
H<sub>2</sub>O
```
# sup Tag 
This tag is used to designate the text as superscript. For example, when we say m2, it would be correct to use the value 2 as a superscript.

**Example:**
```html
m<sup>2</sup>
```
# Comment Lines in HTML 
Comment lines are generally blocks written by the person who wrote the code as a reminder. Because comment lines are not visible to the end user, they can only be seen by looking at the source of the page. Therefore, remember that comments can be read by anyone. When defining, everything between the lines starting with ```<!--``` and ending with ```-->``` is perceived as a comment.

**Example:**
```html
<!-- I wrote a paragraph example here --> 
<p> this is a paragraph </p>
```
In the example above, even if there is an ```<html>``` tag in the comment line, **it will not appear**.

# Links in HTML
When an article is clicked on your web page, you need to close it or create a link to another page or another file on another website. While doing this, we create it with the ```<a>``` tag in HTML.

**Example:**
```html
<a href="https://google.com/tr">go to google</a>
```
When you click on Go to Google here, you will go to **google.com.tr**. In this way, a link is made from one page to another page. 

As seen in the example, the href attribute is used to determine the address to go to when clicked. The ```<a>``` tag does not only contain the href attribute, it can be used with many other attributes.

# Target Attribute in HTML
Apart from href, there is also a target attribute. With this attribute, we determine how the connection will be opened. It has to take one of the following as the value;

```_self```: this is the default value, it opens in the current page.
 
```_blank```: opens the link in a new page. 

```iframeName```: opens the link within the specified iframe.

**Example:**
```html
<a href="https://venge.io/" target="_blank">Venge</a>
```
When clicked, Venge will open in a new tab. There is also the option to open within iframes. Let's give him an **example:**
```html
<p> Click <a href="https://venge.io/" target="browser">to open Venge!
    
<iframe name="browser" width="600" height="300"></iframe>
```
# Images (Pictures) in HTML 
In HTML, images are organized with the ```<img>``` tag. The ```<img>``` tag does not imply poor quality and is an example of a self-closing tag type. Let's put it together and examine it.

**Example:**
```html
<img src="URL">
```
In this example, a link to an image is given to the src attribute. Here, if you wish, you can remove the site address and give the image link. In other words, if the above example was to be displayed on this site, it could also be defined as ```/upload/img/test.jpg```.

# subAttribute 
This attribute represents an expression that alternatively describes the image when there is a problem with the image to be displayed and it cannot be displayed in some way.

**Example:**
```html
<img src="upload/cicek.png" alt="red rose flower">
```
Here, if the cicek.png file cannot be read, it will appear as Red Rose Flower.
![Screenshot_2023-11-16-00-21-59-691-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/967225d2-4df6-43c4-8f45-f3d5350d12dc)

# width and height Attributes 
The width and height attributes are used to determine the width and height of the image.

**Example:**
```html
<img src="upload/cicek.png" alt="red rose flower" width="200" height="100">
```
Here we set the image to 200px in width and 100px in height. The value entered in the width and height values must be a number and is always interpreted in px.

# Showing the Image in Another File 
Let's say you want to display another image in a higher directory of the directory you are working in. Then we use ```../``` to go to the previous directory and select the image.

**Example:**
```html
<img src="../img/test.png" alt="Test">
```
Instead of the directory where you run this code, it will go to a higher directory and search for test.png under the img folder. If we wanted to go 2 upper folders, we would use ```../../```.
# Showing Images in Link 
We learned about the anchor tag in the previous lesson. Now let's see how the two tags are used together.

**Example:**
```html
<a href="URL">
    <img src="img/file" alt="name">
</a>
```
# Linking to Images

**Example**
```html
<a href="URL">
    <img src="image.png">
</a>
```
# HTML <map> Tag 
We can link by marking certain points on the image with the ```<map>``` tag. Let's look at an example now.
```html
<img src="https://prototurk.com/upload/img/cihaz.jpg" alt="devices" usemap="#ptmap">

<map name="ptmap">
    <area shape="rect" coords="105,249,161,366" href="telephone.html" alt="Telephone">
    <area shape="rect" coords="238,172,386,366" href="tablet.html" alt="Tablet">
    <area shape="rect" coords="444,95,834,408" href="computer.html" alt="Computer">
</map>
```
Initial value ```(105)``` - Distance from left Second 
value ```(249)``` - Distance from top Third value 
```(161)``` - Distance from left + width Fourth value 
```(366)``` - Distance from top + height

The point to note here is that we used ```usemap="#ptmap"``` in the ```<img>``` tag. Note that the ptmap value is equal to the name attribute in the ```<map>``` tag. Then we started marking in the ```<map>``` tag. We used the ```<area>``` tag to mark it. In the ```<area>``` tag, we first said ```shape="rect"``` to specify the shape, that is, we determined the shape as a rectangle. Then we gave the coordinates by saying ```coords=""```. We determine the coordinates as follows.
![IMG_20231115_213849.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/6c0736b7-bdb6-4160-a281-8a6a1eb69718)

# Tables in HTML
Tables consist of rows and columns. In addition, the table has a header, the content part, and a bottom part called the footer. Of course, each of these has a tag equivalent in HTML.

**Example:**
```html
<table border="1" width="100%">
    <tbody>
        <tr>
            <td>KAAN</td>
            <td>26</td>
        </tr>
        <tr>
            <td>Cem</td>
            <td>22</td>
        </tr>
    </tbody>
</table>
```
![Screenshot_2023-11-16-00-23-06-065-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/d08b27d0-f81b-4f59-bb09-c779ba62a5dc)
Now, as you can guess, the ```<table>``` tag represents the table here, while ```border="1"``` is used to determine the lines of the table. We will do this with CSS later, but for now we can set the frame to 1 to see the examples. And as you noticed, other table tags are written inside this tag. We also used ```width="100%"``` to set the width of the table to 100%. ```<tbody>``` is the tag containing the content of the table. It contains ```<tr>``` tags for rows and ```<td>``` tags for columns. For tables with more than one row, more than one ```<tr>``` is added.
#Table Header
The ```<thead>``` tag is used to determine the header part of the table. It contains the ```<tr>``` tag again for the rows, but this time the ```<th>``` tag for the columns. Let's give an example right away;
```html
<table border="1" width="100%">
    <thead>
        <tr>
            <th>month</th>
            <th>earning</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>January</td>
            <td>100$</td>
        </tr>
        <tr>
            <td>February</td>
            <td>200$</td>
        </tr>
    </tbody>
</table>
```
![Screenshot_2023-11-16-00-23-38-154-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/17b1c416-48a9-4df7-875b-1f156d965444)
# Table Footer
At the same time, the ```<tfoot>``` tag is used to determine the footer of the table. In this context, the ```<table>``` tag actually consists of 3 tags, ```<thead>``` for the header, ```<tbody>``` for the table content, and ```<tfoot>``` tag for the footer. Let's make it meaningful with an example

**Example:**
```html
<table border="1" width="100%">
    <thead>
        <tr>
            <th>month</th>
            <th>earning</th>
        </tr>
    </thead>
    <tbody>
       <tr>
            <td>January</td>
            <td>100$</td>
        </tr>
        <tr>
            <td>February</td>
            <td>200$</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td>Total</td>
            <td>300$</td>
        </tr>
    </tfoot>
</table>
```
![Screenshot_2023-11-16-13-22-01-163-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/30bddba8-a449-4928-a7f2-c1580690eaca)
# Colspan and rowspan Attributes 
In a table The colspan attribute is used to combine columns in a table, and the rowspan attribute is used to combine rows.

**Example:**
```html
<table border="1" width="100%">
    <thead>
        <tr>
            <th>Year</th>
            <th>Name</th>
            <th>Occupation</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="2">2019</td>
            <td>KAAN</td>
            <td>Web Developer</td>
        </tr>
        <tr>
            <td colspan="2">Cem - Web Developer</td>
        </tr>
    </tbody>
</table>
```
In this example, I combined the 2 rows by adding the 1st column, that is, the year value, in the first row, ```rowspan="2"```. So, as you can see in the 2nd line, I did not write the year again because I combined the 2 lines at the top. In the 2nd row, this time I combined 2 columns. I did this by typing ```colspan="2"```. In other words, I printed the Name and Profession fields in a single column.
![Screenshot_2023-11-16-13-30-56-938-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/8a845d54-6924-4f65-b162-140186cb0d3c)
# Lists in HTML
In HTML, lists are divided into ordered and unordered. Unordered lists are written in the ```<ul>``` tag, ordered lists are written in the ```<ol>``` tag. And each list element must be written within the ```<li>``` tag.
# Unordered List <ul> 
We will use the ```<ul>``` tag to create an unordered list.

**Example:**
```html
<ul>
    <li>lemonade</li>
    <li>coffee</li>
    <li>tea</li>
</ul>
```
There is a filled circle at the beginning of each list element, you can change these by giving the ```type``` attribute if you wish. You can give the following values: 
```circle``` - hollow circle 
```disc``` - solid circle 
```square``` - solid square

**Example:**
```html
<ul type="square">
    <li>Lemonade</li>
    <li>coffe</li>
    <li>tea</li>
</ul>
```
# Sorted List <ol> 
The ```<ol>``` tag is used to create an ordered list.

**Example:**
```html
<ol> 
   <li>What is HTML?</li> 
   <li>Getting Started with HTML</li> 
   <li>Tags in HTML</li> 
</ol>
```
You can use the ```start``` attribute to specify where the counting starts

**Example:**
```html
<ol> start="3" >
   <li>What is HTML?</li> 
   <li>Getting Started with HTML</li> 
   <li>Tags in HTML</li> 
</ol>
```