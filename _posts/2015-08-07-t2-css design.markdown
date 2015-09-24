---
layout: post
title:  "Technical Entry 2 - CSS Design"
date:   2015-08-07
categories: blog entry
---
An important part of creating a webpage is placing each piece (or element) of your webpage in the correct spot. You wouldn’t want text boxes to overlap with images or even an image next to a text box, when it’s actually suppose to be placed above the text box. In CSS we call this positioning and it’s exactly what it sounds like. There are different ways to control the positioning of elements on a webpage and one of the most important ones uses the display property. To understand the display property in CSS, it’s important to picture each element on a webpage as a box. So, when you use the display property to adjust the position of an element, whether its text or an image, think of it like you are positioning the box that the element sits in.

Two important values of the display property are, block and inline-block . When you give an element the property of block, the element is set to take up the entire width of a screen. Therefore, the only open location for other elements to take would be the space above and below. When an element is set to inline-block, the element retains the block shape but will now default to sitting next to (or inline) with the other elements.

In the first example that I’ve included below you will see each element with the value: block. Even though it looks like you could fit more than one element next to each other, using block stacks the elements on top of one another. On the right side of the image, you will see the CSS coding that gives the element div a display of block.

In the second example, you will see the elements with a display value of inline-block. Instead of being stacked up on top of each other, they are laying on the same line in the webpage. On the right of the image, you will notice that all of the elements have been given a display value of inline-block.

Display: Block
<img src="/imgs/ML-devtools-column.png" />

Display: Inline-Block
<img src="/imgs/ML-devtools-row.png" />