## Ordered Lists

### (ol)

### (The ordered list is created with
### the (ol) element.
### (li)
### Each item in the list is placed
### between an opening (li) tag
### and a closing </li> tag. (The li
### stands for list item.

## Unordered Lists
### (ul)
### The unordered list is created with the (ul) element.
### (li) Each item in the list is placed between an opening (li) tag and a closing (/li) tag. (The li stands for list item.) Browsers indent lists by default.

## Definition Lists
### (dl) The definition list is created with the (dl) element and usually consists of a series of terms and their definitions.
### Inside the (dl) element you will usually see pairs of (dt) and (dd) elements.
### (dt) This is used to contain the term being defined (the definition term).
### (dd)
### This is used to contain the definition.


## Nested Lists

### You can put a second list inside an (li) element to create a sublist or nested list. Browsers display nested lists indented further than the parent list. In nested unordered lists, the browser will usually change the style of the bullet point too.

## Boxes:

### At the beginning of this section on CSS, you saw how CSS treats each HTML element as if it lives in its own box. You can set several properties that affect the appearance of these boxes. In this chapter you will see how to: Control the dimensions of your boxes Create borders around boxes Set margins and padding for boxes Show and hide boxes

## Limiting Width: Some page designs expand and shrink to fit the size of the user's screen. In such designs, the min-width property specifies the smallest size a box can be displayed at when the browser window is narrow, and the max-width property indicates the maximum width a box can stretch to when the browser window is wide.

## Limiting Height:
### In the same way that you might want to limit the width of a box on a page, you may also want to limit the height of it. This is achieved using the min-height and max-height properties.

## Overflowing Content:
### The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values: 
### hidden
### This property simply hides any extra content that does not fit in the box.
### scroll
### This property adds a scrollbar to the box so that users can scroll to see the missing content.

## Border, Margin & Padding:

## Border
### Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another.

## Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.


## Padding
### Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents.


## Border Images
### The border-image property applies an image to the border of any box. It takes a background image and slices it into nine pieces.

## Box Shadows

### The box-shadow property allows you to add a drop shadow around a box. It works just like the text-shadow property that you met on page 288. It must use at least the first of these two values as well as a color:

### Horizontal offset Negative values position the shadow to the left of the box. 
### Vertical offset Negative values position the shadow to the top of the box

# java script

## SWITCH STATEMENTS:
### A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.