# Introductory HTML and JavaScript 
## Introductory HTML
 HTML is the standard markup language for creating Web pages.
### Structure 
Structure refers to the practice of using HTML on content to convey meaning (semantics) and to describe how blocks of information are structured to one another. Examples: "this is a list" (ol, ul, li), "this is headings and subheadings" (h1, h2, ..., h6), "this section is related to" (a etc.."

![](https://slideplayer.com/slide/14870912/90/images/3/Structure+of+HTML+Document.jpg)
The HTML code (in blue) is made up of characters that live inside angled
brackets — these are called HTML elements. Elements are usually
made up of two tags : an opening tag and a closing tag. (The closing tag
has an extra forward slash in it.) Each HTML element tells the browser
something about the information that sits between its opening and
closing tags.

HTML Uses Elements
to Describe the
Structure of Pages

HTML Tags: Tags are the starting and ending parts of an HTML element. They begin with < symbol and end with > symbol. Whatever written inside < and > are called tags.
 
 Attributes require a name and a value.

HTML elements: Elements enclose the contents in between the tags. They consist of some kind of structure or expression. It generally consists of a start tag, content and an end tag.

![](https://learn-to-code.london.cloudapps.digital/images/lesson-1/image7.png)

### Extra Markup
DOCTYPES tell browsers which version of HTML you
are using.

 You can add comments to your code between the
**<**!-- and --**>** markers.

 The id and class attributes allow you to identify
particular elements.

 The <**div**> and <**span**> elements allow you to group
block-level and inline elements together.

 <**iframes**> cut windows into your web pages through
which other pages can be displayed.

The <**meta**>  tag allows you to supply all kinds of
information about your web page.

 Escape characters are used to include special
characters in your pages such as <, >, and ©.

### HTML5 Layout

The new HTML5 elements indicate the purpose of
different parts of a web page and help to describe
its structure.

 The new elements provide clearer code (compared
with using multiple <**div**> elements).
![](https://codebridgeplus.com/wp-content/uploads/html5-new.jpg)
![](https://i.pinimg.com/originals/12/9c/54/129c5480493ee9da20c43b6771e03a2d.jpg)

**Older browsers that do not understand HTML5
elements need to be told which elements are
block-level elements.**

### Process & Design 
 a process that
you can use when you are creating a new
website.

It looks at who might be visiting your site and how to ensure
the pages feature the information those visitors need. It also
covers some key aspects of design theory to help you create
professional looking sites. In this chapter, we will look at:

● How to understand the audience your site may attract and
what information they will expect to find on it

● How to organize information so that visitors can find what
they are looking for

● Design theory for presenting information in a way that
helps visitors achieve their goals

● Design tips to help you create more attractive and
professional sites

Every website should be designed for the
target audience—not just for yourself or the
site owner. It is therefore very important to
understand who your target audience is.
and  It's important to understand who your target audience
is, why they would come to your site, what information
they want to find and when they are likely to return.

for this moment u need  Site maps 
 to allow you to plan the structure of a site.
 ![](https://online.visual-paradigm.com/repository/images/d21171a5-f3dc-46e5-ba38-3590ed5c6e52/site-map-diagram-design/company-website-sitemap.png)


 And We use Wireframes to  allow you to organize the information that
will need to go on each page.
![](https://i.pinimg.com/originals/08/66/8b/08668befd34d816306ca9013a1ae9e3d.png)

Visual hierarchy

Most web users do not read entire pages. Rather, they skim to find
information. You can use contrast to create a visual hierarchy that gets
across your key message and helps users find what they are looking for.

**SIZE**
Larger elements will grab users'
attention first. For this reason it
is a good idea to make headings
and key points relatively large.

**COLOR**
Foreground and background
color can draw attention to key
messages. Brighter sections tend
to draw users' attention first.

**Style**
An element may be the same
size and color as surrounding
content but have a different style
applied to it to make it stand out.


Design is about communication. Visual hierarchy helps
visitors understand what you are trying to tell them.

**Concise**
Ideally, the navigation should
be quick and easy to read. It is
a good idea to try to limit the
number of options in a menu to
no more than eight links. These
can link to section homepages
which in turn link to other pages.

**Clear**
Users should be able to predict
the kind of information that
they will find on the page
before clicking on the link.
Where possible, choose single
descriptive words for each link
rather than phrases.

**Selective**
The primary navigation should
only reflect the sections or
content of the site. Functions
like logins and search, and legal
information like terms and
conditions and so on are best
placed elsewhere on the page.


# JavaScript 
## Introduction
JavaScript allows you yo make web pages more interactive by accessingand modifying the content  and markup used in a web page while it is being viewed in the browser.

#### ACCESS CONTENT
You can use JavaScript to select any
element, attribute, or text from an
HTML page. For example:

• Select the text inside all of the **<hl>**
elements on a page

• Select any elements that have a
c 1 ass attribute with a value of note

• Find out what was entered into a
text input whose id attribute has a
value of ema i 1 
#### MODIFY CONTENT
You can use JavaScript to add
elements, attributes, and text to the
page, or remove them. For example:

• Add a paragraph of text after the
first **<**hl**>** element

• Change the value of c 1 ass
attributes to trigger new CSS rules
for those elements

• Change the size or position of an
**<**i mg**>** element 

#### PROGRAM RULES
You can specify a set of steps for
the browser to follow (like a recipe),
which allows it to access or change the
content of a page. For example:

• A gallery script could check which
image a user clicked on and display
a larger version of that image.

• A mortgage calculator could collect
values from a form, perform a
ca lculation, and display repayments.

• An animation could check the
dimensions of the browser window
and move an image to the bottom
of the viewable area (also known as
the viewport).
#### REACT TO EVENTS
You can specify that a script should run
when a specific event has occurred. For
example, it could be run when:

• A button is pressed

• A link is clicked (or tapped) on

• A cursor hovers over an element

• Information is added to a form

• An interval of time has passed

• A web page has finished loading

## The ABC of Programming
A what is the script and how do I creat one 

A script is a series of instructions that the computer
can follow in order to achieve a goal.

Each time the script runs, it might only use a subset of
all the instructions.

Computers approach tasks in a different way than
humans, so your instructions must let the computer
solve the task prggrammatically.

To approach writing a script, break down your goal into
a series of tasks and then work out each step needed
to complete that task (a flowchart can help). 
 
B how do coputers fit in with the world around them?
 Computers create models of world using data.

 The models use objects to represent phisical things objects can have : properties that tell us about the object
   ![](https://cdn.programiz.com/sites/tutorial2program/files/javascript-object-properties.png)
  , methodes
  ![](https://dmitripavlutin.com/static/d0597f7819971bf2b124b653b673eb29/05127/cover-2.png) 
  
  that perform tasks using the properties of the object, events whoch are triggered when a user interacts with the computer.

 Programmers can write code to say when this event 
  occurs run that code.
  ![](https://cope-ali.github.io/cope-ali261.github.io/img/HTMLevents.png)

Web browsers use HTML markup to create a model of the web page. Each element creates its own node .

To make web pages interactive, you write code that uses the browsers model of the web page.











 

 


 