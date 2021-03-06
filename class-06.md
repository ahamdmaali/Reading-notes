# OBJECTS
### Objects group together a set of variables and functions to create a model  of a something you would recognize from the real world. In an object, variables and functions take on new names.

# The Document Object Model "DOM".
### DOM specifies  how browsers should create a model of an HTML  page and how JavaScript can access and update the  contents of a web page while it is in the browser window. 

## two primary areas covered by DOM:
1. MAKING A MODEL OF THE  HTM L PAGE.
2. ACCESSING AND CHANGING THE HTML PAGE.

## DOM Tree:
### As a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes. 
 
 ## Accessing and updating the DOM tree involves two steps:
 1. Locate the node that represents the element you want to work with.
 2. Use its text content, child elements, and attributes.

# Caching DOM Queries
### Methods that find elements in the DOM tree are called DOM queries.

### DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes.
##### METHODS THAT RETURN A SINGLE ELEMENT NODE:
1. getElementByld('id').
2. querySelector('css selector').

##### METHODS THAT RETURN ONE OR MORE ELEMENTS (AS A NODELIST):
1. getElementsByClassName('class').
2. getElementsByTagName('tagName').

### NODELISTS: DOM QUERIES THAT RETURN MORE THAN ONE ELEMENT

### LOOPING THROUGH A NODELIST
#### It involves finding out how many items are in the Nodelist, and then setting a counter to loop through them, one-by-one. Each time the loop runs, the script checks that the counter is less than the total number of items in the Nodelist. 

## TRAVERSING THE DOM
### When you have an element node, you can select another element in relation to it using these five properties. This is known as traversing the DOM.
1. parentNode
2. previousSibling
3. nextSibling 
4. firstChild
5. lastChild 

# HOW TO GET/UPDATE ELEMENT CONTEN
### ACCESS & UPDATE A TEXT NODE WITH NODEVALUE:
#### When you select a text node, you can retrieve or amend the content of it using the node Va 1 ue property. 
### ACCESSING & CHANGI NG A TEXT NODE:
#### To work with text in an element, first the element node is accessed and then its text node. The text node has a property called node Value which returns the text in that text node. You can also use the node Va 1 ue property to update the content of a text node.
### ACCESS & UPDATE TEXT WITH TEXTCONTENT (& INN ERTEXT):
#### The textContent property allows you to collect or update just the text that is in the containing element (and its children). 
### ACCESSING TEXT ONLY:
#### In order to demonstrate the difference between textContent and i nnerText, this example features a CSS rule to hide the contents of the <em> element. The script starts off by getting the content of the first list item using both the textContent property and i nnerText. It then writes the values after the list. Finally, the value of the first list item is then updated to say sourdough bread. This is done using the textContent property.
### ACCESS & UPDATE TEXT & MARKUP WITH INNERHTML:
#### Using the i nnerHTML property, you can access and amend the contents of an element, including any child elements.

## ADDING ELEMENTS USING DOM MANIPULATION
#### DOM manipulation offers another technique to add new content to a page (rather than innerHTML). It involves three steps: 
1. createElement ().
2. createTextNode().
3. appendChild().

## REMOVING ELEMENTS VIA DOM MANIPULATION
#### DOM manipulation can be used to remove elements from the DOM tree. 
1. STORE THE ELEMENT TO BE REMOVED IN A VARIABLE.
2. STORE THE PARENT OF THAT ELEMENT IN A VARIABLE.
3. REMOVE THE ELEMENT FROM ITS CONTA INING ELEMENT.

# ATTRIBUTES
### CREATING ATTRIBUTES & CHANGING THEIR VALUES
#### The setAttri bute() method allows you to update the value of any attribute. It takes two parameters: the attribute name, and the value for the attribute. 
### REMOVING ATTRIBUTES
#### To remove an attribute from an element, first select the element, then call removeAtt r i bute () . It has one parameter: the name of the attribute to remove.

 

