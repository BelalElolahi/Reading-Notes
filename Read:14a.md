# CSS Transforms, Transitions, and Animations
## Transforms
The transform CSS property lets you rotate, scale, skew, or translate an element. It modifies the coordinate space of the CSS visual formatting model.
##### Transform: matrix(1, 2, 3, 4, 5, 6);





##### transform: translate(120px, 50%);

   




##### transform: scale(2, 0.5);






##### transform: rotate(0.5turn);

   




##### transform: skew(30deg, 20deg);

  




##### transform: scale(0.5) translate(-100%, -100%);

![](https://www.htmldog.com/figures/transform.png)

## Transitions
CSS transitions provide a way to control animation speed when changing CSS properties. Instead of having property changes take effect immediately, you can cause the changes in a property to take place over a period of time. For example, if you change the color of an element from white to black, usually the change is instantaneous. With CSS transitions enabled, changes occur at time intervals that follow an acceleration curve, all of which can be customized.

Animations that involve transitioning between two states are often called implicit transitions as the states in between the start and final states are implicitly defined by the browser.


![](https://slideplayer.com/slide/3827203/13/images/56/CSS3+Transition+Properties.jpg)
![](https://d33wubrfki0l68.cloudfront.net/02ca5906d1d4d7e7725e83029a0ff236a2756988/7b62e/images/css/back-to-basics-css-transitions/anatomy-of-transition.svg)


## Animations
CSS animations make it possible to animate transitions from one CSS style configuration to another. Animations consist of two components, a style describing the CSS animation and a set of keyframes that indicate the start and end states of the animation’s style, as well as possible intermediate waypoints.

There are three key advantages to CSS animations over traditional script-driven animation techniques:

They’re easy to use for simple animations; you can create them without even having to know JavaScript.
The animations run well, even under moderate system load. Simple animations can often perform poorly in JavaScript. The rendering engine can use frame-skipping and other techniques to keep the performance as smooth as possible.
Letting the browser control the animation sequence lets the browser optimize performance and efficiency by, for example, reducing the update frequency of animations running in tabs that aren't currently visible.
![](https://stuyhsdesign.files.wordpress.com/2017/03/animation-properties.png)
![](https://i.pinimg.com/originals/27/11/01/271101e60be5a3bcd1fd57dfd6065d7e.png)
