# Error Handling & Debugging
### ERRORS
Errors are statements which don't let the program run properly. There are three main types of errors that can occur while compiling a JavaScript program. These errors include syntax errors, runtime errors, and logical errors.

There are seven types of built-in error objects in
JavaScript. You'll see them below:
![](https://files.speakerdeck.com/presentations/5ad67abfcb8743499474344873514b08/slide_17.jpg)



### HOW TO DEAL WITH ERRORS

##### 1: DEBUG THE SCRIPT TO FIX ERRORS
If you come across an error while writing a script
(or when someone reports a bug), you will need to
debug the code, track down the source of the error,
and fix it.

You will find that the developer tools available in
every major modern browser will help you with
this task. In this chapter, you will learn about the
developer tools in Chrome and Firefox. (The tools in
Chrome are identical to those in Opera.)
![](https://miro.medium.com/max/1024/1*dahHaMDlEHzN_oXTam7Ibw.jpeg)

##### 2: HANDLE ERRORS GRACEFULLY
You can handle errors gracefully using try, catch,
throw, and f i na 1 ly statements.
Sometimes, an error may occur in the script for a
reason beyond your control. For example, you might
request data from a third party, and their server
may not respond. In such cases, it is particularly
important to write error-handling code.
In the latter part of the chapter, you will learn how to
gracefully check whether something will work, and
offer an alternative option if it fails. 

HANDLING EXCEPTIONS

If you know your code might fail, use try, catch, and finally.
Each one is given its own code block.

**try {**

**II Try to execute this code**

**catch (exception) {**

**II If there is an exception, run this code**

**fina lly {**

**II This always gets executed **

![](https://i.ytimg.com/vi/GYWUr7xlK-w/maxresdefault.jpg)