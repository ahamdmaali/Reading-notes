# LAYOUT 

## Controlling the Position of Elements
#### CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolut positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.

## Normal Flow (position:static)
#### In normal flow, each block-level element sits on top of the next one.

## Relative Positioning(position:relative)
#### Relative positioning moves an element in relation to where it would have been in normal flow.

## Absolute Positioning(position:absolute)
#### When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.) 

## Fixed Positioning(position:fixed)
#### Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed. 
#### It positions the element in relation to the browser window. Therefore, when a user scrolls down the page, it stays in the exact same place. It is a good idea to try this example in your browser to see the effect.

## Overlapping Elements
#### When you use relative, fixed, or absolute positioning, boxes can overlap. If boxes do overlap, the elements that appear later in the HTML code sit on top of those that are earlier in the page. If you want to control which element sits on top, you can use the z-index property. Its value is a number, and the higher the number the closer that element is to the front.

## Floating Elements(float)
#### The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.Anything else that sits inside the containing element will flow around the element that is floated. When you use the floatproperty, you should also use the width property to indicate how wide the floated element should be. If you do not, results can be inconsistent but the box is likely to take up the full width of the containing element (just like it would in normal flow).

## A Fixed width Layout 
#### To create a fixed width layout, the width of the main boxes on a page will usually be specified in pixels (and sometimes their height, too).

# A Liquid Layout
#### The liquid layout uses percentages to specify the width of each box so that the design will stretch to fit the size of the screen.

##### TO learn more about layout, raed ducett book, ch15.

