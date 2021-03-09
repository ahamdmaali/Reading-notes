# Forms
#### HTML borrows the concept of a form to refer to different elements that allow you to collect information from visitors to your site.

## Form Controls
1. ADDING TEXT: Text input (single-line) Used for a single line of text such as email addresses and names.
2. Password input: Like a single line text box but it masks the characters entered.
3. Text area: For longer areas of text, such as messages and comments.
4. Making Choices: For use when a user must select one of a number of options.
5. Checkboxes: When a user can select and unselect one or more options.
6. Drop-down boxes: When a user must pick one of a number of options from a list.
7. Submitting Forms: To submit data from your form to another web page.
8. Uploading Files: Allows users to upload files (e.g. images) to a website.

## How Forms Work 
#### A user fills in a form and then presses a button to submit the information to the server.

###### To learn more about forms, raed duckett html book, ch7.

# Lists

## Bullet Point Styles
#### The list-style-type property allows you to control the shape or style of a bullet point (also known as a marker). 
## Images for Bullets
#### You can specify an image to act as a bullet point using the list-style-image property. The value starts with the letters url and is followed by a pair of parentheses. Inside the parentheses, the path to the image is given inside double quotes.
## Positioning the Marker
#### Lists are indented into the page by default and the list-styleposition property indicates whether the marker should appear on the inside or the outside of the box containing the main points.
## List Shorthand
#### As with several of the other CSS properties, there is a property that acts as a shorthand for list styles. It is called list-style, and it allows you to express the markers' style, image and position properties in any order.
## Table Properties
#### You have already met several properties that are commonly used with tables. 
## Border on Empty Cells
#### If you have empty cells in your table, then you can use the empty-cells property to specify whether or not their borders should be shown.Since browsers treat empty cells in different ways, if you want to explicitly show or hide borders on any empty cells then you should use this property.
## Gaps Between Cells(border-spacing, border-collapse)
#### The border-spacing property allows you to control the distance between adjacent cells. By default, browsers often leave a small gap between each table cell, so if you want to increase or decrease this space then the border-spacing property allows you to control the gap.The value of this property is usually specified in pixels. You can specify two values if desired to specify separate numbers for horizontal and vertical spacing.

###### To learn more about lists, raed duckett html book, ch14.


# Events
### W hen you browse the web, your browser registers different types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events.

## Typs Of Events:
#### UI EVENTS 
1. load 
2. unload 
3. error 
4. resize
5. scroll 
#### KEYBOARD EVENTS
1. keydown 
2. keyup
3. keypress
#### MOUSE EVENTS 
1. click and dbl click
2. mouse down/up
3. mousemove
4. mouseover 
5. mouseout

## TERMINOLOGY
### EVENTS FIRE OR ARE RAISED 
##### When an event has occurred, it is often described as having fired or been raised. In the diagram on the right, if the user is tapping on a link, a cl ick event would fire in the browser. 
### EVENTS TRIGGER SCRIPTS 
##### Events are said to trigger a function or script. When the click event fires on the element in this diagram, it could trigger a script that enlarges the selected item.

## HTML5 EVENTS
Here are three page-level events that have been 
included in versions of the HTMLS spec that 
have become popular very quickly.
1. DOMContentLoaded.
2. hashchange.
3. beforeunload.

### USER INTERFACE EVENTS
##### User interface CUI) events occur as a result of interaction with the browser window rather than the HTML page contained within it.
### LOAD
##### The load event is commonly used to trigger scripts that access the contents of the page. 
### FOCUS & BLUR EVENTS
##### The HTML elements you can interact with, such as links and form elements, can gain focus. These events fire when they gain or lose focus.
### MOUSE EVENTS
##### The mouse events are fired when the mouse is moved and also when its buttons are clicked. 
### KEYBOARD EVENTS
##### The keyboard events are fired when a user interacts with the keyboard (they fire on any kind of device with a keyboard). 
### FORM EVENTS
##### There are two events that are commonly used with forms. In particular you are likely to see submit used in form validation. 
### MUTATION EVENTS & OBSERVERS
##### Whenever elements are added to or removed from the DOM, its structure changes. This change triggers a mutation event. 

###### To learn more about Events, raed duckett JS book, ch6.

