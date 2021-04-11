# class01

## Text

***Headings and paragraphs***

> *Headings* : HTML defines six levels of headings. A heading element implies all the font changes, paragraph breaks before and after, and any white space necessary to render the heading. The heading elements are H1, H2, H3, H4, H5, and H6 with H1 being the highest (or most important) level and H6 the least
> *paragraphs* : The HTML < p > element defines a paragraph. A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.

***Bold, italic***

* *Blod* : By enclosing words in the tags < b > and < /b > we can make characters appear bold. The < b > element also represents a section of text that would be presented in a visually different way although the use of the < b > element does not imply any additional meaning
* **italic** : By enclosing words in the tags < i > and < /i > we can make characters appear italic. The < i > element also represents a section of text that would be said in a different way from surrounding content

***Superscript and Subscript***

* *< sup >* : The < sup > element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power
* *< sub >* : The < sub > element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas

***Semantic Markup***
> There are some text elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages — they are known as semantic markup

* **< strong >** : The use of the < strong > element indicates that its content has strong importance. For example, the words contained in this element might be said with strong emphasis. By default, browsers will show the contents of a < strong > element in bold

8 **< em > : The < em > element indicates emphasis that subtly changes the meaning of a sentence. By default browsers will show the contents of an < em > element in italic

### What is CSS ?

>CSS is the language for describing the presentation of Web pages, including colors, layout, and fonts. It allows one to adapt the presentation to different types of devices, such as large screens, small screens, or printers. CSS is independent of HTML and can be used with any XML-based markup language

***How CSS works ?***

![CSS](data:image/png;base64,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)

> The browser loads the HTML (e.g. receives it from the network). It converts the HTML into a DOM (Document Object Model). ... The browser parses the fetched CSS, and sorts the different rules by their selector types into different "buckets", e.g. element, class, ID, and so on

***Rules, properties, and values***

> A CSS rule is a grouping of one or more CSS properties which are to be applied to one or more target HTML elements. A CSS rule consists of a CSS selector and a set of CSS properties. The CSS selector determines what HTML elements to target with the CSS rule
> CSS value definition syntax, a formal grammar, is used for defining the set of valid values for a CSS property or function. ... A component can be a keyword, some characters considered as a literal, or a value of a given CSS data type or of another CSS property

#### What is JavaScript ?

> *JavaScript* : ("JS" for short) is a full-fledged dynamic programming language that can add interactivity to a website. It was invented by Brendan Eich (co-founder of the Mozilla project, the Mozilla Foundation, and the Mozilla Corporation)

***If statements***

Very often when you write code, you want to perform different actions for different decisions
> You can use conditional statements in your code to do this
> In JavaScript we have the following conditional statements:

1. Use if to specify a block of code to be executed, if a specified condition is true
2. Use else to specify a block of code to be executed, if the same condition is false
3. Use else if to specify a new condition to test, if the first condition is false
4. Use switch to specify many alternative blocks of code to be executed
! [if statement](https://i.ytimg.com/vi/2ExYFqgCh2I/maxresdefault.jpg)

***Loops***
> JavaScript supports different kinds of loops:

1. for - loops through a block of code a number of times
2. for/in - loops through the properties of an object
3. for/of - loops through the values of an iterable object
4. while - loops through a block of code while a specified condition is true
5. do/while - also loops through a block of code while a specified condition is true
