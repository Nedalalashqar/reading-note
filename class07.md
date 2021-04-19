# Readings : Object-Oriented Programming, HTML Tables

***What's a Table?***

1. The < table > tag defines an HTML table. Each table row is defined with a < tr > tag. Each table header is defined with a < th > tag. Each table data/cell is defined with a < td > tag. By default, the text in < th > elements are bold and centered. By default, the text in < td > elements are regular and left-aligned.
2. A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results.

***Basic Table St ructure***

* *< table >* : The < table > element is used to create a table. The contents of the table are written out row by row.
* *< tr >* : You indicate the start of each row using the opening < tr > tag. (The tr stands for table row.)
* *< td >* : Each cell of a table is represented using a < td > element. (The td stands for table data.)

## Domain Modeling

> Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.
> A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

***Model epic fails videos***

> Imagine you've been tasked to build a program that models the popularity of epic fail videos. After months of painstaking research, you've determined that the two essential metrics for gauging popularity are an epic rating and whether or not the video has animals.
> Since you'll be modeling the popularity of many types of videos—parkour epic fails, corgi epic fails, etc.—you'll want to build self-contained objects with the same attributes and behaviors. That way, when you need to change the algorithm for determining popularity, the changes will be small and targeted.
> As you read this article, type out and run all code samples you come across. Do not copy and paste. Writing out and testing your code will help you remember how to implement domain models in JavaScript later.
