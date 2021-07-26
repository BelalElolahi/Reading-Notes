# HTML Lists, Control Flow with JS, and the CSS Box Model
## HTML Lists
There are three types of HTML lists: 

Ordered lists are lists where each item in the list is
numbered. For example, the list might be a set of steps for
a recipe that must be performed in order, or a legal contract
where each point needs to be identified by a section
number.
![](https://scaldes.github.io/images/ListsOrdered.jpg)

 Unordered lists are lists that begin with a bullet point
(rather than characters that indicate order).
![](https://scaldes.github.io/images/ListsUnordered.jpg)


 Definition lists are made up of a set of terms along with the
definitions for each of those terms.
![](https://i0.wp.com/www.tutorialbrain.com/wp-content/uploads/2019/01/Description-List.jpg?fit=474%2C397&ssl=1)

 
## CSS Boxes
In CSS, the term "box model" is used when talking about design and layout.

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:
![](https://media.gcflearnfree.org/content/5ef2084faaf0ac46dc9c10be_06_23_2020/box_model.png)
and you can us width, hight to box scale control

overflow :
The overflow property tells the
browser what to do if the content
contained within a box is larger
than the box itself. It can have
one of two values:  

**hidden**
This property simply hides any
extra content that does not fit in
the box.

**scroll**
This property adds a scrollbar to
the box so that users can scroll
to see the missing content.


Centering Content
![](https://www.freecodecamp.org/news/content/images/2020/08/centering-css-tweet.jpeg)



display

 


![](https://www.myprograming.com/wp-content/uploads/2021/06/css-display-property-1.jpg)

visibility

This property can take two
values:

**hidden**
This hides the element.

**visible**
This shows the element
![](https://www.jquery-az.com/wp-content/uploads/2015/11/4.1-CSS-display-visibility.png)

box-shadow
Horizontal offset
Negative values position the
shadow to the left of the box.

Vertical offset
Negative values position the
shadow to the top of the box.

Blur distance
If omitted, the shadow is a solid
line like a border.

Spread of shadow
If used, a positive value will
cause the shadow to expand in
all directions, and a negative
value will make it contract
![](https://codeconvey.com/wp-content/uploads/2019/05/box-shadow-effect-in-css.jpg)

border-radius


To create more complex shapes,
you can specify different
distances for the horizontal and
the vertical parts of the rounded
corners.

For example, this will create a
radius that is wider than it is tall:

border-radius: 80px 50px;
## JS Control Flow 
A normal program is not a sequential execution of expressions or statements one after the other. It will have certain conditions to be checked or it will have certain number of iterations. When we check for certain conditions to execute further then it called as decision statements. If the condition in decision statements are true then one set of instructions are executed, if false then another set of instructions are executed. This kind of decision is cannot be done using conditional operator. That will be mainly used to return single line of action / result. When we have to perform series of operation, we use IF conditions.
![](https://dotnettrickscloud.blob.core.windows.net/img/c/if-else-statement.png)
![](https://cdn.programiz.com/sites/tutorial2program/files/js-if-else-statement.png)

switch statment 

switch statement is a type of selection control mechanism used to allow the value of a variable or expression to change the control flow of program execution via search and map.
![](https://slideplayer.com/slide/6322656/21/images/2/The+JavaScript+Switch+Statement.jpg)

