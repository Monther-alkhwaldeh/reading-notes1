
# WHAT IS AN OBJECT?
## Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.

## IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES
### If a variable is part of an object, it is called a property. Properties te ll us about the object, such as the name of a hotel or the number of rooms it has.
### Each individual hotel might have a different name and a different number of rooms.


## IN AN OBJECT: FUNCTIONS BECOME
### KNOWN AS METHODS If a function is part of an object, it is called a method. Methods represent tasks that are associated with the object. For example, you can check how many rooms are available by subtracting the number of booked rooms from the total number of rooms.



-------------------------------------



# The Document Object Model (DOM):
### specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

## MAKING A MODEL OF THE HTML PAGE
### When the browser loads a web page, it creates a model of the page in memory.
### The DOM specifies the way in which the browser should structure this model using a DOM tree.
### The DOM is called an object model because the model (the DOM tree) is made of objects. Each object represents a different part of the page loaded in the browser window.

# ACCESSING AND CHANGING THE HTML PAGE
### The DOM also defines methods and properties to access and update each object in this model, which in turn updates what the user sees in the browser. You will hear people call the DOM an Application Programming Interface (API). User interfaces let humans interact with programs; APls let programs (and scripts) talk to each other. 
### The DOM states what your script can "ask the browser about the current page, and how to tell the browser to update what is being shown to the user.

## SELECT AN INDIVIDUAL ELEMENT NODE:

## Here are three common ways to
### select an individual element: get El ement Byld () Uses the value of an element's id attribute (which should be unique within the page).

## querySelector ()
### Uses a CSS selector, and returns the first matching element.

## SELECT MULTIPLE ELEMENTS (NODELISTS):
### getElementsByClassName() Selects all elements that have a specific value for their cl ass attribute.

### getElementsByTagName()
### Selects all elements that have the specified tag name 

### querySelectorAll()
### Uses a CSS selector to select all matching elements.


### TRAVERSING BETWEEN ELEMENT NODES:
### You can move from one element node to a related element node.
### parentNode
### Selects the parent of the current element node (which will return just one element).

### previousSibl ing / nextSibl ing Selects the previous or next sibling from the DOM tree.
### firstChild / lastChild
### Select the first or last child of the
### current element.





