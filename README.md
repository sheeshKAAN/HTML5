Greetings everyone, if you want to get a good start in software, starting with web-based HTML will be a good start for you.

My aim in this github project is to give you HTML lessons for those who are new to the software and want to advance on the web.

I will tell you about these html tutorials, but before looking at the tutorials, I want to briefly talk a little about the web.
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
# What is WebGL?
It is a web standard that aims to provide 3D graphic drawing in the web environment. Based on OpenGL ES 2.0, WebGL is not very different from OpenGL ES, although it has undergone minor changes to adapt to languages such as JavaScript with automatic memory management. It makes it possible to draw 3D graphics on HTML5's Canvas element without requiring the installation of any plug-in in the compatible web browser.

Yes, after briefly summarizing the web part, we can now get into HTML.

# What is HTML?
HTML **(Hypertext Markup Language)** is a markup language used when creating web pages, it forms the basis of the web page. CSS, which makes it look more beautiful and organized, is JavaScript, which allows it to be used in a more dynamic structure. HTML5 is the fifth version of the HTML markup standard, one of the core technologies of the Internet.

Yes, now that we have made the definition, we can move on to the software part. First of all, let's start with the basic elements, we will encounter these elements frequently.

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
Everything is going well so far, now let's talk a little about the qualities.

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

**Editor:**
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

We will see what we have learned in more detail in the following sections, these are just preliminary information.
Now let's take a look at the other tags.

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

**Editor:**
![Screenshot_2023-11-16-00-15-25-167-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/8ced6e1e-5417-4cf1-bff9-ffc23f7a5d1c)

Let's give more detailed information about these.
# ```<b>``` and ```<strong>``` Tags 
It thickens when visible on both labels. The difference between each other is that the ```<b>``` tag's markup only makes it bold, while the ```<strong>``` tag's markup both makes it bold and indicates that the text is an important text when interpreted by the browsers.

**Example:**
```html
<b>Hello KAAN</b>
<strong>Have are you?</strong>
```
# ```<i>``` and ```<em>``` Tags
It is used for the slope of the text in both labels. The difference between them is that marking the ```<i>``` tag only shows italics, while marking the ```<em>``` tag both shows italics and indicates that that text is highlighted when interpreted by browsers.

**Example:**
```html
<i>italic writing</i>
<em>eat, work, run, dance</em>
```
# ```<small>``` Tag 
The ```<small>``` tag is used to make text smaller than it appears. Even if the text is written in capital letters, the text in this label appears smaller than the other letters.

**Example:**
```html
Can <small>this text appear smaller</small> when these texts are normal?
```

**Editor:**
![Screenshot_2023-11-16-00-17-01-335-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/1490eda6-50c3-496f-8443-9232d655b0f4)
# ```<mark>``` Tag
We use the ```<mark>``` tag in HTML to draw and highlight the text with a yellow pen.

**Example:**
```html
this text is normal<mark>this text is crossed out in yellow</mark>
```

**Editor:**
![Screenshot_2023-11-16-00-17-35-530-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/24d768ee-f903-48d0-9d41-c4eea683da4a)
# ```<del>``` Tag
We mark the strikethrough text with the ```<del>``` tag.

**Example:**
```html
Lemonade price <del> 1$ </del> 5$
```

**Editor:**
![Screenshot_2023-11-16-00-18-01-805-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/863779a8-b705-48fe-827d-3ee34fc7b2fd)
# ```<ins>``` Tag
The ```<ins>``` tag is used when adding new posts to deleted posts using ```<del>```.

**Example:**
```html
Lemonade price <del> 1$ </del> <ins> 5$ </ins>
```

**Editor:**
![Screenshot_2023-11-16-00-18-34-773-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/0ddeebe3-21b7-49b4-b8f0-80632ab2e8a3)
# ```<sub>``` Tag 
This tag is used to designate the text as a subscript. For example, when we say H2O, it would be correct to use the value 2 as a subscript.

**Example:**
```html
H<sub>2</sub>O
```
# ```<sup>``` Tag 
This tag is used to designate the text as superscript. For example, when we say m2, it would be correct to use the value 2 as a superscript.

**Example:**
```html
m<sup>2</sup>
```
Now that we have detailed the tags a bit, we can move on to the comment lines. Comment lines will really come in handy.

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
<img src="upload/flower.png" alt="red rose flower">
```
Here, if the cicek.png file cannot be read, it will appear as Red Rose Flower.


**Editor:**
![Screenshot_2023-11-16-00-21-59-691-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/967225d2-4df6-43c4-8f45-f3d5350d12dc)

# width and height Attributes 
The width and height attributes are used to determine the width and height of the image.

**Example:**
```html
<img src="upload/flower.png" alt="red rose flower" width="200" height="100">
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
# HTML map Tag 
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

**Editor:**
![IMG_20231115_213849.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/6c0736b7-bdb6-4160-a281-8a6a1eb69718)

Yes, now let's take a look at the lists and tables.

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

**Editor:**
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
**Edıtor:**
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

**Editor:**
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

**Editor:**
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

**Editor:**
![Screenshot_2023-11-16-20-08-02-096-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/f13deec3-f468-462d-a59b-65d0b0fc06c7)
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

**Edıtor:**
![Screenshot_2023-11-16-20-08-28-649-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/89983e46-90ad-43ee-962a-de202fc7866e)
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

**Editor:**
![Screenshot_2023-11-16-20-08-58-896-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/29a6c941-986e-46cd-a25d-7da12180d48b)
You can use the ```start``` attribute to specify where the counting starts

**Example:**
```html
<ol> start="3" >
   <li>What is HTML?</li> 
   <li>Getting Started with HTML</li> 
   <li>Tags in HTML</li> 
</ol>
```

**Editor:**
![Screenshot_2023-11-16-20-10-34-221-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/24ced8cd-27c2-45bb-bdf3-e59891d0e9c7)
# Using Nested Lists 
In general, we will need to use nested lists frequently. When using it, a new list is written inside the ```<li>``` tag. Let's give an example

**Example:**
```html
<ul>
    <li>HTML</li>
    <li>
        CSS
        <ul>
            <li>SASS</li>
            <li>LESS</li>
        </ul>
    </li>
    <li>
        JavaScript
        <ul>
            <li>
                Client-side
                <ul>
                    <li>jQuery</li>
                    <li>React</li>
                </ul>
            </li>
            <li>
                Server-side
                <ul>
                    <li>Nodejs</li>
                </ul>
            </li>
        </ul>
    </li>
    <li>
        PHP
        <ul>
            <li>Laravel</li>
            <li>Symfony</li>
        </ul>
    </li>
</ul>
```

**Editor:**
![Screenshot_2023-11-16-23-16-11-831-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/b8574ed3-c289-47b2-9e90-955180093607)
# Description List in HTML 
You can also create description lists in HTML. So you can create a list and use these labels to explain what each element does. The <dl> tag is used to create the list, the ```<dt>``` tag is used for the term to be explained, and the ```<dd>``` tag is used for the description.

**Example:**
```html
<dl>
    <dt>Mustafa Kemal Atatürk</dt>
    <dd>Founder of the Republic of Türkiye.</dd>
    <dt>Einstein</dt>
    <dd>Nobel Prize-winning German theoretical physicist of Jewish origin</dd>
</dl>
```

**Editor:**
![Screenshot_2023-11-16-23-21-56-959-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/3e4d8d4a-474e-4bb8-981d-75c1a79cf86e)

List tags are the tags we use to create menus when doing web design. Even if it doesn't make sense right now, it can gain meaning with CSS. To make an analogy, HTML forms the trunk and branches of the tree, and CSS forms the green leaves.

# View Values in HTML 
Each HTML tag has a default display value. The default display value of most tags is either **block-level** tag or **inline-level** tag view.
# Block Level Labels 
Block level tags always start on a new line and take up the entire width, meaning they appear as 100%. In this way, it becomes easier to understand block level labels. The most common tag we can give to block level tags is the ```<div>``` tag

# ```<div>``` Tag
In fact, the ```<div>``` tag represents sections in the HTML page. So every new div means a new section. When we want to separate sections, we generally use the ```<div>``` tag. However, we generally meet our block level label needs from this label, it may not mean much right now because it does not give a different appearance as an output when used, the purpose here is not to give a view anyway but to customize the view by using this label. Of course, CSS is required for this. Right now you just need to know that there is such a tag and that it is a block level tag and is one of the most used tags.

**Example:**
```html
<div> Hello World </div> We are testing.
```

Of course, the ```<div>``` tag is normally used with certain attributes. You can find these qualities in detail on this label's own page. When you run the example above, you will notice that there is no appearance change, but you will see that the 2nd typed content starts from the bottom, I hope this was useful in understanding the block level tag. The ```<p>``` tag, which we frequently used in previous lessons, was also a **block-level** tag as a display level and started from a new line.

**Editor:**
![Screenshot_2023-11-16-23-35-22-423-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/36c76f8b-2e3a-4e34-aec2-10e86516a0bf)

# Block Level Tags
```<address>``` 
```<article>``` 
```<aside>``` 
```<blockquote>``` 
```<canvas>``` 
```<dd>``` 
```<div>``` 
```<dl>``` 
```<dt>``` 
```<fieldset>``` 
```<figcaption>``` 
```<figure>``` 
```<footer>``` 
```<form>``` 
```<h1>-<h6>``` 
```<header>``` 
```<hr>``` 
```<li>``` 
```<main>``` 
```<nav>``` 
```<noscript>``` 
```<ol>``` 
```<p>``` 
```<pre>``` 
```<section>``` 
```<table>``` 
```<tfoot>```
```<ul>```
```<video>```

The ```<div>``` tag is an unstyled HTML tag. It is used as a container for other HTML tags. It is more related to CSS. The ```<div>``` tag is an unstyled HTML tag. It is often used as a container for other HTML tags.

# Inline Level Labels
The most used of this tag type is the ```<span>``` tag. As its name suggests, it is an inline tag type, meaning that there will be no distortion or change even when marking within the text. Just like the ```<div>``` tag, the ```<span>``` tag is an unstyled tag that is mainly used to identify inline elements and apply CSS or JavaScript to them.

**Example:**
```html
During a normal text, <span>this field written in span</span> will not look any different from the others.
```

# Inline Level Tags
```<a>```
```<abbr>```
```<acronym>```
```<b>```
```<bdo>```
```<big>```
```<br>```
```<button>```
```<cite>```
```<code>```
```<dfn>```
```<em>```
```<i>```
```<img>```
```<input>```
```<kbd>```
```<label>```
```<map>```
```<object>```
```<output>```
```<q>```
```<samp>```
```<script>```
```<select>```
```<small>```
```<span>```
```<strong>```
```<sub>```
```<sup>```
```<textarea>```
```<time> ```
```<tt> ```
```<var>```

It is not really important what the display level of a label is because these display levels can be changed with the help of CSS. So ```<div>``` is normally a block level tag, but we can turn it into an inline level tag with the help of CSS.

# id and class Attributes in HTML 
Under normal circumstances, I will not explain each attribute specifically, but since these two attributes are the attributes we will use most frequently when doing **front-end** coding, I would like to mention them.

**Example:**
```css
<div id="container"> ... </div>
```
As you can see, the attribute usage is always the same as attribute="value". The important thing here is what does this id attribute do? In fact, it doesn't change anything in terms of appearance. To understand the purpose of using this attribute, it is necessary to understand a little CSS. The room is like this; 

In CSS, it's all about choosing a tag and applying styles. For example, when we want to select all divs, we write a CSS code like this. (you may not find this meaningful right now, it doesn't matter)

**Example:**
```css
div {
    background-color: yellow;
    color: red;
}
```
In this code, we selected all ```<div>``` tags and made the background color yellow and the text color red. However, in front-end coding, it is often necessary to select and style specific divs, not every div. In this case, we use the ```id and``` ```class``` attribute. In our HTML example above, we added the attribute ```id="container"``` to the ```<div>``` tag. If it is defined as ```id```, it is defined within the framework of some rules.

- IDs have been redesigned throughout the page. This means that you have an ```id=test"``` tag, that is, you cannot give the ```test``` value to another tag. For this reason, id is usually given to inclusive tags or tags that have only a single function throughout the page. 
- The sign tag taken with ID is used as ```#container``` when used on the CSS side. Here is our example of ```container``` values in HTML. So, then, I would write in CSS like this that I want to process by selecting divs with container id values;

**Example:**
```css
#container {
    background: yellow;
    color: red;
}
```
It was healthier this way, we selected all tags whose id was container instead of the ```<div>``` tag. If we wanted to select only div tags whose id is container, we would change it like this:
```css
div#container {
    background: yellow;
    color: red;
}
```
In this example, we first select the name of the tag to be specifically selected, that is, div in the example here, and then, if it is defined with id, we make the selection by putting a **#** sign in front of it and writing its value.

# class Attribute 
We have already explained the ```id``` attribute, the class attribute is also used for the same function. So specifically to be able to mark a tag and then edit it in CSS. However, the difference from the id attribute is that ```class``` attributes can be used more than once with the same name. This is a very useful thing because we write the same ```class``` name in tags that have the same style but have slight differences and solve the problem with a single CSS code.

**Example:**
```html
<a href="#" class="button">Normal Buton</a>
<a href="#" class="button button-red">Red Buton</a>
<a href="#" class="button button-green">Green Buton</a>
<a href="#" class="button button-blue">Blue Buton</a>
```

In the codes above, we used the ```<a>``` tag to create a button, in this example our button goes to an address. Now, when you look at the codes above in the editor, nothing will appear visually because we will give this with CSS in a moment, but let's examine the attribute used first.

Now, we added a class named ```button``` to each of them, but we also specified a second class name for each of them. This is because, in my opinion, these 3 buttons will look the same, only the background colors will be different. Therefore, instead of selecting each one separately and writing separate CSS, I gave the same class name to all 3 of them and will bring them all to the same appearance at once with CSS. Additionally, I will write the code that will change the background color in CSS for the 2nd class names. In short, even if you don't understand CSS, our CSS codes will look like this;

```css
a.button {
    background-color: #333;
    color: #fff;
    display: inline-block;
    line-height: 50px;
    padding: 0 15px;
    border-radius: 3px;
    text-decoration: none;
}

a.button.button-red {
    background-color: red;
}

a.button.button-blue {
    background-color: blue;
}

a.button.button-green {
    background-color: green;
}
```
Don't be intimidated by the length of the code. Actually, we are learning HTML right now, but since CSS and JavaScript are directly connected to HTML, I will add such information. You will learn all the details from the CSS and JavaScript pages in the following processes. Now let's examine the codes one by one.

```background-color: #333;``` - Here we set the background color to black by default.

```color: #fff;``` - Here we set the default text color as white.

```display: inline-block;``` - Here we set the display value as inline-block, we have seen these display values in previous lessons. Normally the <a> tag was an inline tag, but we set it to be both inline and block with CSS. This means that it will be inline, but it will also be at the block level to show the other CSS properties I will give.

```line-height: 50px;``` - Here we set the line height as 50px, which automatically centered the text from top and bottom within 50px.

```padding: 0 15px;``` - Here, we gave 15px space on the right and left. In this way, the text will look smoother and will not stick to the right or left.

```border-radius: 5px;``` - Here, we softened all four edges of the button by 3px.

```text-decoration: none;``` - Here, ```<a>``` tags are underlined by default, we removed this line.

```a.button.button-red``` - The explanation here is actually, among the ```<a>``` tags, select the tag or tags whose ```class``` value is ```button``` and which is also ```button-red```. And we made its color red.

```a.button.button-blue``` - We set the background color of the class value button-blue to blue.

```a.button.button-green``` - We changed the background color of the class value button-green to green.

```html
<a href="#" class="button">Normal Button</a>
<a href="#" class="button button-red">Red Button</a>
<a href="#" class="button button-green">Green Button</a>
<a href="#" class="button button-blue">Blue Button</a>

<style>
a.button {
    background-color: #333;
    color: #fff;
    display: inline-block;
    line-height: 50px;
    padding: 0 15px;
    border-radius: 3px;
    text-decoration: none;
}

a.button.button-red {
    background-color: red;
}

a.button.button-blue {
    background-color: blue;
}

a.button.button-green {
    background-color: green;
}
</style>
```

**Editor:**
![Screenshot_2023-11-17-21-58-26-538-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/20901878-d75d-4d25-b374-e10046612703)

There is only one tag here that we don't know right now, which is the ```<style>``` tag, I didn't explain it because it is related to CSS. But to put it simply, CSS codes can normally be written in 3 different ways on the page. One is by adding a file with the extension .css to the page with the ```<link>``` tag, the second is by using the ```style=""``` attribute in the tags on the page, and the third is by writing CSS code directly into the ```<style>``` tags. In this example we did exactly that.

I think we understand clearly why we need to use these attributes. In other words, it is an attribute entirely related to CSS.

**Don't Forget!**
A tag can have both ```id``` and ```class``` attributes at the same time.

#Using Iframe in HTML
Iframes are used within web pages to embed and display other web pages.

Of course, we cannot do this for every web page because most web pages prevent viewing with iframes. I will show you how to do this at the end of the article. Now let's examine the codes of how to create an iframe;
```html
<iframe src="https://venge.io"></iframe>
```

**Editor:**
![Screenshot_2023-11-17-21-43-45-977-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/198d6e94-c8d4-45b5-8e3e-04bcf05d3ff9)

The iframe tag doesn't mean much without its attributes. Here we determined the path of the page to be displayed in the frame with the ```src``` attribute.

# width and height Attributes in iframe
The width and height attributes are used to determine the width and height of the frame.

**Example:**
```html
<iframe src="https://venge.io" width="380" height="480"></iframe>
```

**Edıtor:**
![Screenshot_2023-11-17-21-45-17-975-edit_com.codeliber.html.jpg](https://github.com/sheeshKAAN/HTML5-learning-guide./assets/132504490/8329756d-0279-48c5-9b9a-5d0f543986b2)
Values are again given in ```px```. However, it is also accepted as a percentage. So ```width="100%"``` will work.

Remove Default Border in Iframe
Iframes come with a border by default. To remove this, adding ```frameborder="0"``` will be sufficient.

**Example:**
```html
<iframe src="https://venge.io" frameborder="0">
```
It is also possible to edit this with CSS, for example;
```html
<iframe src="https://venge.io" style="border: none;"></iframe>
```
# Closing the Iframe Scroll
To prevent the content you upload in the iframe from being scrolled, you can give the scrolling attribute a value of no.

**Example:**
```html
<iframe name="frame_name" src="https://venge.io" scrolling="no"></iframe>
```

# Showing the Target Link in Iframe
If we want the page to open in the iframe when the ```<a>``` tag is clicked, we should use the following method:
```html
<a href="url" target="frame_name">open frame_name</a>
    
<iframe name="frame_name"></iframe>
```

The important thing here is that the ```target="frame_name"``` part in the ```<a>``` tag and the ```name="frame_name"``` part in the ```<iframe>``` tag are equal. Because we specify the target with the target attribute in the ```<a>``` tag. In other words, we select the frame that will open when clicked.

#Preventing Your Web Page from Opening with Iframe
I'm already saying that to do this, it is necessary to use different technologies. I will share with you an example made with Javascript.

**Example:**
```html
<script>
if (self != top) {
	top.location.replace(location.href);
}
</script>
```
What's new here is the ```<script>``` tag, which allows us to write Javascript code within HTML pages.

JavaScript is a programming language that developers use to create interactive web pages. It allows you to dynamically add and change the contents of HTML pages. JavaScript is a powerful programming language that brings web pages to life and is used to make them interactive.

# File Paths in HTML
Although this issue may seem unimportant, people who are new to HTML courses usually give the following way when they want to show images or something;

**Example:**
```html
<img src="C:\Users\test\Desktop\a.png">
```
In this logic, they think that it will work when they put it on the server, but they are wrong. When giving file paths, we can give them as follows;

# File Paths
- ```<img src="image.jpg">```
It calls the **image.jpg** file located in the same location as the current folder.
- ```<img src="img/image.jpg">```
Calls the **image.jpg** file in the **img** folder under the current folder.
- ```<img src="/img/image.jpg">```
It calls the **image.jpg** file in the **img** folder under the main folder. The difference from the one above is that if it is preceded by **/**, it represents the home directory.
- ```<img src="../image.jpg">```
It calls the **image.jpg** file located in a folder above the current folder.
- ```<img src="url/image.jpg">```
This is the clearest way to give, but it is unnecessarily long. In fact, it is exactly the same as **/image.jpg**.

In HTML, we generally need to specify file paths for;
- HTML pages
- Images
- CSS Files
- JavaScript Files
- etc.

# Specifying the Default Path in HTML
The ```<base>``` tag is used to specify the default path in HTML. And it is written in the ```<head>``` tag in our codes.

**Example:**
```html
<head>
    ...
    <base href="url">
    ...
</head>
```
After doing this, if I use it as ```<img src="upload/img/resim.jpg">```, it will actually be interpreted as follows; ```<img src="url/upload/img/image.jpg">```

So, to be precise, we can use this tag on our pages. You may be working on your own computer now, but in the future you will need to buy yourself a hosting or server so that you can publish the web pages you create. In such cases, this label will come in handy. If you look at the source code of this site right now, you will see the same code. To view the source, you can use the combination **CTRL + U on Windows** or **command + option + u** on macOs.

# Headers in HTML
In our first HTML lesson, we learned about the ```<head>``` tag and said that it is one of the basic tags. We also mentioned that what is written in the ```<body>``` tag will be shown to the end user, and all other codes that will run in the background must be written in ```<head>```. In fact, in the same example, we determined the title of the web page by using the ```<title>``` tag, which is also a default tag, within the ```<head>``` tag.

It is meant to provide the title of each tag defined within the <head> tag. These include the following tags:

```<title>``` - Sets the page title

```<style>``` - Enables the use of CSS within HTML

```<meta>``` - Used to define any header information.

```<link>``` - Used to include a CSS file on the page

```<script>``` - Enables the use of javascript in HTML. It is also useful for calling javascript files.


```<base>``` - This tag, which we learned in the last lesson, determines the default path.

# ```<style>``` Tag
This tag allows us to write CSS code within the HTML page.

**Example:**
```html
<style>
body {
    background-color: #eee;
}
h1 {
    font-size: 30px;
}
</style>
```

Although it is generally written in the ```<head>``` tag, it can also be written in the body from time to time. But there is a problem: since the codes are interpreted from top to bottom, the CSS codes must always be at the top, otherwise the styles will arrive after the page loads, which creates an ugly appearance.

# ```<link>``` Tag
This tag defines the relationship between the current page and the page to be called. For example, we can call a CSS file.

**Example:**
```html
<link rel="stylesheet" type="text/css" href="stil.css">
```

# ```<meta>``` Tag
The ```<meta>``` tag is used to define headers on web pages. For example, you can view the page's character encoding, description, keyword, author, etc. Used to define headers.

Browsers use headers to determine how to display the page. Search engines generally interpret this header information, so determining this header information correctly is very important for SEO. SEO(Search Engine Optimization) ensures that web pages appear higher in search engines.

# Usage areas of the ```<meta>``` tag

- It is used to determine the character encoding of the page.
```html
<meta charset="UTF-8">
```
- It is used to determine the title of the page.
```html
<title> ... </title>
```
- It is used to determine the description of the page.
```html
<meta name="description" content="...">
```
- It is used to determine the keywords of the page.
```html
<meta name="keywords" content="HTML, CSS, JavaScript">
```
- It is used to determine the author of the page.
```html
<meta name="author" content="sheeshKAAN">
```
- It is used to refresh the page within a specified period of time. (In this example, we set it to 10 seconds)
```html
<meta http-equiv="refresh" content="10">
```
