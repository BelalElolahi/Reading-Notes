# HTML Links, JS Functions, and Intro to CSS Layout
## HTML Links 
Links are created using the **<**a**>** element. Users can click on anything
between the opening **<**a**>** tag and the closing **<**/a**>** tag. You specify
which page you want to link to using the href attribute
![](https://www.computerhope.com/jargon/h/html-tag.gif)

Relative link 
![](https://i.pcmag.com/imagery/encyclopedia-terms/href-_href.fit_lim.size_1050x.gif)
## JS Functions
### What is the functions:
#### Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.

#### A JavaScript function can be defined using function keyword.

#### Syntax:
###### //defining a function
###### function <function-name>()
###### {
   ######  // code to be executed
###### };

###### //calling a function
###### <function-name>();

#### Here are several advantages of using functions in your code:

##### Use of functions enhances the readability of a program. A big code is always difficult to read. Breaking the code in smaller Functions keeps the program organized, easy to understand and makes it reusable.
##### The C compiler follows top-to-down execution, so the control flow can be easily managed in case of functions. The control will always come back to the main() function.
##### It reduces the complexity of a program and gives it a modular structure.
##### In case we need to test only a particular part of the program we will have to run the whole program and figure out the errors which can be quite a complex process. Another advantage here is that functions can be individually tested which is more convenient than the above mentioned process.
##### A function can be used to create our own header file which can be used in any number of programs i.e. the reusability.
###  Objects 
In JavaScript, an object is a standalone entity, with properties and type. Compare it with a cup, for example. A cup is an object, with properties. A cup has a color, a design, weight, a material it is made of, etc. The same way, JavaScript objects can have properties, which define their characteristics.
![](https://cdn.programiz.com/sites/tutorial2program/files/javascript-object-properties.png)

In JavaScript, almost "everything" is an object.

Booleans can be objects (if defined with the new keyword)
Numbers can be objects (if defined with the new keyword)
Strings can be objects (if defined with the new keyword)
Dates are always objects
Maths are always objects
Regular expressions are always objects
Arrays are always objects
Functions are always objects
Objects are always objects
All JavaScript values, except primitives, are objects.
JavaScript variables can also contain many values.

Objects are variables too. But objects can contain many values.

Object values are written as name : value pairs (name and value separated by a colon).



## CSS Layout
At this point we've already looked at CSS fundamentals, how to style text, and how to style and manipulate the boxes that your content sits inside. Now it's time to look at how to place your boxes in the right place in relation to the viewport, and one another. We have covered the necessary prerequisites so we can now dive deep into CSS layout, looking at different display settings, modern layout tools like flexbox, CSS grid, and positioning, and some of the legacy techniques you might still want to know about.

Normal flow

Elements on webpages lay themselves out according to normal flow - until we do something to change that. This article explains the basics of normal flow as a grounding for learning how to change it.

Flexbox
Flexbox is a one-dimensional layout method for laying out items in rows or columns. Items flex to fill additional space and shrink to fit into smaller spaces. This article explains all the fundamentals. After studying this guide you can test your flexbox skills to check your understanding before moving on.

Grids

CSS Grid Layout is a two-dimensional layout system for the web. It lets you lay content out in rows and columns, and has many features that make building complex layouts straightforward. This article will give you all you need to know to get started with page layout, then test your grid skills before moving on.

Floats

Originally for floating images inside blocks of text, the float property became one of the most commonly used tools for creating multiple column layouts on webpages. With the advent of Flexbox and Grid it has now returned to its original purpose, as this article explains.

Positioning

Positioning allows you to take elements out of the normal document layout flow, and make them behave differently, for example sitting on top of one another, or always remaining in the same place inside the browser viewport. This article explains the different position values, and how to use them.

Multiple-column layout

The multiple-column layout specification gives you a method of laying content out in columns, as you might see in a newspaper. This article explains how to use this feature.
Responsive design
As more diverse screen sizes have appeared on web-enabled devices, the concept of responsive web design (RWD) has appeared: a set of practices that allows web pages to alter their layout and appearance to suit different screen widths, resolutions, etc. It is an idea that changed the way we design for a multi-device web, and in this article we'll help you understand the main techniques you need to know to master it.
![](https://www.positronx.io/wp-content/uploads/2019/11/angular-css-grid-layout-7256-001.jpg)




