Quick fix to change color of a logo.
------------------------------------

### On Master branch

* Based on CSS-Tricks article
[http://codepen.io/noahblon/post/coloring-svgs-in-css-background-images]

* Heart icon from the example provided is a SVG file with fill property (red), RadioTimes does not have this property at all in SVG. [https://s3-us-west-2.amazonaws.com/s.cdpn.io/18515/heart.svg]

* Original base color for RadioTimes logo was black, changed to red by adding fill="red" into SVG.

* Correct hue/saturation etc. values will specify the output color (fill to be removed from SVG)

### On Version2 branch

* Simplified code in CSS, no need for hue/saturation background-color CSS property used instead

* No need to change base colour in RadioTimes SVG, overriden by background-color property

