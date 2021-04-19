# Read: 08 - More CSS Layout

***Layout***

1. Key Concepts in Positioning Elements :
    * *Building Blocks* : Everything in CSS has a box around it, and understanding these boxes is key to being able to create layouts using CSS, or to align elements with other elements and an HTML document consists of the building blocks of it: Tags: The HTML tag surrounds the content and applies meaning to it. It is written in parentheses. Attribute: An attribute in HTML provides additional information about the element, and it is applied within the start tag.
        1. *Block-level elements* : A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can). The < div > element is a block-level element. Examples include: < h1 > < p > < ul > < li >
        2. *Inline elements* : An inline element does not start on a new line and only takes up as much width as necessary. This is an inline < span > element inside a paragraph. Examples of inline elements: < span > . Examples include: < img > < b> < i >
    * *Containing Elements* : The size and position of an element are often impacted by its containing block. Most often, the containing block is the content area of an element's nearest block-level ancestor, but this is not always the case. In this article, we examine the factors that determine an element's containing block.

***Controlling the Position of Elements***
> Positioning elements with CSS in web development isn’t as easy as it seems. Things can get quickly complicated as your project gets bigger and without having a good understanding of how CSS deals with aligning HTML elements, you won't be able to fix your alignment issues.

* *Normal flow* : Normal Flow, or Flow Layout, is the way that Block and Inline elements are displayed on a page before any changes are made to their layout. The flow is essentially a set of things that are all working together and know about each other in your layout. Once something is taken out of flow it works independently.
* *Relative Positioning* : The position property specifies the type of positioning method used for an element. Elements are then positioned using the top, bottom, left, and right properties. However, these properties will not work unless the position property is set first. They also work differently depending on the position value.

> **There are five different position values:**

1. static
2. relative
3. fixed
4. absolute
5. sticky

* *Absolute positioning* : An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed). However; if an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.
* *Fixed Positioning* : An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element. A fixed element does not leave a gap in the page where it would normally have been located.
* *The float Property* : The float property is used for positioning and formatting content e.g. let an image float left to the text in a container. In its simplest use, the float property can be used to wrap text around images.

  * **The float property can have one of the following values:**

    1. left - The element floats to the left of its container

    2. right - The element floats to the right of its container

    3. none - The element does not float (will be displayed just where it occurs in the text). This is default

    4. inherit - The element inherits the float value of its parent

***Links***

* *HTML links are hyperlinks* : You can click on a link and go to another document. The most important attribute of the < a > element is the href attribute, which indicates the destination of the link, and the link text is the part that will be visible to the reader. Clicking on the link text will send the reader to the specified URL. for **example** : < a href="http://www.imdb.com" > IMDB < /a >

* *Directory Structure* : Organizing Files and Folder Structure for Web Pages It is a good idea to organize your code by placing the pages for each different section of the site into a new folder. Folders are referred to as directories on websites.
![Directory Structure](https://stuyhsdesign.files.wordpress.com/2015/09/directory-structure1.png)
  * *Structure* : The top-level is known as the root folder. (In this example is know as the root folder called examples-site.) The root folder is contains all the other files and folders for a website.
  * *Relationships* : The relationship between files and folders on a website is described using the same terminology as a family tree. The example-site folder is a parent of the activities, music and theater folders. The  activities, music and theater folders are children of the example-site folder.
  * *Homepages* : The main homages of a site written in HTML is called index.html ( and the homepage of each section in a child folder). Web servers are usually set up to return to the index.html file if no file name is specified. Therefore, if you enter example-site.com it will return example-site.com/index.html, and example-site.com/music will return example-site.com/music/index.html.

  * *Relative URLs* : A relative URL (defined in [RFC1808]) doesn't contain any protocol or machine information. Its path generally refers to a resource on the same machine as the current document. ... Relative URLs are resolved to full URLs using a base URL.
