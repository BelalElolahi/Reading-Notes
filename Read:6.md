# JS Object Literals; The DOM
## JS Object Literals
Objects in JavaScript, just as in many other programming languages, can be compared to objects in real life. The concept of objects in JavaScript can be understood with real life, tangible objects.

In JavaScript, an object is a standalone entity, with properties and type. Compare it with a cup, for example. A cup is an object, with properties. A cup has a color, a design, weight, a material it is made of, etc. The same way, JavaScript objects can have properties, which define their characteristics.
![](https://i1.wp.com/image.slidesharecdn.com/javascript-110725163050-phpapp01/95/javascript-literacy-2-728.jpg)

Objects and properties

A JavaScript object has properties associated with it. A property of an object can be explained as a variable that is attached to the object. Object properties are basically the same as ordinary JavaScript variables, except for the attachment to objects. The properties of an object define the characteristics of the object. You access the properties of an object with a simple dot-notation:

objectName.propertyName

Copy to Clipboard
Like all JavaScript variables, both the object name (which could be a normal variable) and property name are case sensitive. You can define a property by assigning it a value. For example, let's create an object named myCar and give it properties named make, model, and year as follows:

###### var myCar = new Object();
###### myCar.make = 'Ford';
###### myCar.model = 'Mustang';
###### myCar.year = 1969;
Copy to Clipboard
The above example could also be written using an object initializer, which is a comma-delimited list of zero or more pairs of property names and associated values of an object, enclosed in curly braces ({}):

###### var myCar = {
    make: 'Ford',
    model: 'Mustang',
    year: 1969
};



## The DOM 
Introduction to the DOM

The Document Object Model (DOM) is the data representation of the objects that comprise the structure and content of a document on the web. In this guide, we'll briefly introduce the DOM. We'll look at how the DOM represents an HTML or XML document in memory and how you use APIs to create web content and applications.

What is the DOM?

The Document Object Model (DOM) is a programming interface for HTML 
and XML documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects. That way, programming languages can connect to the page.
 

 ![](https://slidetodoc.com/presentation_image_h/7d5f393805809bab5b11180c363cd426/image-2.jpg)
 ![](https://slidetodoc.com/presentation_image_h/7d5f393805809bab5b11180c363cd426/image-5.jpg)

#### METHODS THAT RETURN A SINGLE ELEMENT NODE:
##### getElementByld( 1 id 1)
Selects an individual element given the value of its i d attribute .
The HTML must have an id attribute in order for it to be selectable.
First supported: IE5.5, Opera 7, all versions of Chrome, Firefox, Safari

##### querySel ector( 1css selector')

Uses CSS selector syntax that would select one or more elements .
This method returns only the first of the matching elements.
First supported: IE8, Firefox 3.5, Safari 4. Chrome 4, Opera 10


#### METHODS THAT RETURN ONE OR MORE ELEMENTS (AS A NODELIST):
##### getEl ementsByClassName( 1class 1 )
Selects one or more elements given the value of their cl ass attribute.
The HTML must have a cl ass attribute for it to be selectable.
This method is faster than querySe 1ectorA11 () .
First supported: IE9, Firefox 3, Safari 4, Chrome 4, Opera 10
(Several browsers had partial I buggy support in earlier versions)
##### getEl ementsByTagName( 1tagName 1)
Selects all elements on the page with the specified tag name.
This method is faster than querySe 1ectorA11 ().
First supported: IE6+, Firefox 3, Safari 4, Chrome, Opera 10
(Several browsers had partial I buggy support in earlier versions)

##### querySelectorAll ( 1css select or•)
Uses CSS selector syntax to select one or more elements and returns all
of those that match.
First supported: IE8, Firefox 3.5, Safari 4, Chrome 4, Opera 10

 ![](https://slidetodoc.com/presentation_image_h/7d5f393805809bab5b11180c363cd426/image-11.jpg)

