# Transforms
![Transforms](https://www.htmldog.com/figures/transform.png)
used to position and alter (change the appearance) elements.
general syntax

div {
  `-webkit-transform: transformType(specific amount);`
    ` -moz-transform: transformType(specific amount);`
       `-o-transform: transformType(specific amount);`
         ` transform: transformType(specific amount);`
* transform Types:
1. **2D Rotate**
transform: rotate(20deg); the value from 0 to 360 degree, a positive value rotates element clockwise, while a negative value rotates element counterclockwise. The default point of rotation is the center of the element, 50% 50%, both horizontally and vertically.
2. **2D Scale**
used to change the appeared size of an element. a value between 0.99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger. the default value is 1.
transform: scale(.75);
use transform: scaleX(number); to scale the width and use transform: scaleY(number);to scale the height and use transform: scale(X-value, Y-value); to scale both width and height each with a didderent scal value. 2D Translate
works like relative positioning. Positive values will push an element down and to the right while negative values will pull an element up and to the left.
3. **2D Skew**
used to deform elements on the horizontal axis, vertical axis, or both. the acceptable values unit is only in degrees.
Transition
## transition:
![transition](https://storage.stfalcon.com/uploads/images/5881e0b98e717.png) 
alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.

- There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay.
- use all keyword instead of the property name to apply transition to all properties.
- transition-duration could have multiple values separated with commas for each transitioned property.
- The transition-timing-function property is used to set the speed in which a transition will move. it’s most popular vaslues are linear, ease-in, ease-out, and ease-in-out.
*linear*: transition moving in a constant speed from one state to another.
*ease-in*: starts slowly and speeds up throughout the transition.
*ease-out*: starts quickly and slows down throughout the transition.
*ease-in-out*: starts slowly, speeds up in the middle, then slows down again before ending.

## Animation
Animation: set multiple points of transition upon different keyframes.


![Animation](https://hackernoon.com/drafts/x84g2geg.png)