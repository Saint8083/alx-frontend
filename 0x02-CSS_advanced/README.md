# 0x02. Advanced CSS

* { } /* select all elements */
section /* select all section tags */
.my-class { } /* select all elements with that class */
.my-block > .my-title { }
.my-block + .my-title { }
.my-block ~ .my-title { }
#my-div /* select the element with that ID  */


CSS (Cascading Style Sheets) are used to style HTML.

CSS works by:

- selecting an HTML element
- choosing a property to alter
- applying a certain value

Colors
The color CSS property sets the color value of a text HTML element.

Colors in CSS are represented most commontly represented by names, hexadecimal or RGB values.

Accessibility tip
When choosing colors for your design, you should always take accessibility into consideration. Modern browsers have now an easy way to show if a color is accessible or not

Code example
p { color: red; }
p { color: #f00; }
p { color: #ff0000; }
p { color: rgb(255,0,0); }
p { color: rgb(100%, 0%, 0%); }
p { color: hsl(0, 100%, 50%); }
