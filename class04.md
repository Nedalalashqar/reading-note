# Links

> HTML links are hyperlinks. You can click on a link and jump to another document. When you move the mouse over a link, the mouse arrow will turn into a little hand. Note: A link does not have to be text. A link can be an image or any other HTML element
**Writing Links**
> Links are created using the < a > element. Users can click on anything between the opening < a > tag and the closing </a> tag. You specify which page you want to link to using the href attribute.
**An example of links**
> < a href="http://www.imdb.com">IMDB</a>
**Types of links**

* Links rom one website to another
* Links from one page to another on the same website
* Links from one part of a web page to another part of the same page
* Links that open in a new browser window
* Links that start up your email program and address a new email to someone
**Directory Structure**

>On larger websites it's a good idea to organize your code by placing the pages for each different section of the site into a new folder. Folders on a website are sometimes referred to as directories.
***Rela tive URLs***
>Relative URLs can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.

## layouts

> *layouts* : control where each element sits on a page and how to create attractive page layouts.

***Key Concepts in Positioning Elements***

1. *Building Blocks* : Block-level boxes start on a new line and act as the main building blocks of any layout, while inline boxes flow between surrounding text. You can control how much space each box takes up by setting the width of the boxes (and sometimes the height, too). To separate boxes, you can use borders, margins, padding, and background colors

2. *Containing Elements* : It is common to group a number of elements together inside a < div > (or other block-level) element. For example, you might group together all of the elements that form the header of a site (such as the logo and the main navigation). The < div > element that contains this group of elements is then referred to as the containing element

***Controlling the Position of Elements***
> CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.

* *Normal flow* : Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. Even if you specify the width of the boxes and there is space for two elements to sit side-byside, they will not appear next to each other. This is the default behavior (unless you tell the browser to do something else).
* *Relative Positioning* : This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed. This does not affect the position of surrounding elements; they stay in the position they would be in in normal flow.
* *Absolute positioning* : This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements (as they simply ignore the space it would have taken up). Absolutely positioned elements move as users scroll up and down the page.
* *Fixed Positioning* : This is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element. Elements with fixed positioning do not affect the position of surrounding elements and they do not move when the user scrolls up or down the page.
* *Floating Elements* : Floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box. The floated element becomes a block-level element around which other content can flow.
