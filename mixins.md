Mixins and Functions

#### Mixins:

**Example Usage**

**@include trbl();**

Is the equivalent of setting the top, bottom left and right to 0.


**@include selectors();**

Applies a set of selectors from the $selector-groups map.
Currently used to apply &:hover &:focus &:active to links.
Used in @include btn();


**@include bg-style()**

Set background repeat, size and position


**@include left-right();**

Add a property to the left and right of a box.


**@include top-bottom();**

Add a property to the top and bottom of a box.


**@include sr-only() ;**

Hide only for screen readers.


#### Functions:

**function: rem-calc();**

Converts one or more pixel values into matching rem values.


**function: svg-url($svg);**

Function to create an optimized svg url


**function: selectors();**

Applies a set of selectors from the $selector-groups map.
Currently used to apply &:hover &:focus &:active to links.


**function (z);**

retrieves the appropriate z index value from $z-layers map


**function (extend-in-map);**

Extends results with override or extend values in declared map.


**function (key);**

Returns values from map for key and sub-key
