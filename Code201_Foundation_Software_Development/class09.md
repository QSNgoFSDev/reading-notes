# Class 09 Forms and JS Events


## HTML Forms
Your first Web Form. How To Structure A Web Form.


- [x] Why are forms so important in web development?
Each time you want to create an HTML form, you must start it by using this element, nesting all the contents inside. Many assistive technologies and browser plugins can discover `<form>` elements and implement special hooks to make them easier to use.


- [x] When designing a form, what are some key things to keep in mind when it comes to user experience?


- [x] List 5 form elements and explain their importance.

The `<label>` element is the formal way to define a label for an HTML form widget. This is the most important element if you want to build accessible forms 

input is for user to put user input for certain set of data in. thats where atttribute type become handy

Password, Email,Boolean,Radio(tick box),checkbox type,

Placehodler, to create emxaple input in a form

Name etc 
type: 'text'

input type 'reset' reset data.





Drop down menu we can use selecet tag. comwith option tag. 

select is parent option


## JavaScript - Introduction To Events.

- [x] How would you describe events to a non-technical friend?

The listener listens out for the event happening, and the handler is the code that is run in response to it happening.

Event is where an object will switch its own property by a "click" of a button

- [x] When using the addEventListener() method, what 2 arguments will you need to provide?

there are 2 parameter we need to add

Firstly, The string "click" to indicate that we want to listen to click event.

Secondly, the function (), to call when event happen.


- [x] Describe the event object. Why is the target within the event object useful?

even object is a parameter within an handler function. e it is automatically passed to event handlers to provide extra features and information

target whitin the event object useful by later, we can get its target value as input to store data.


- [x] What is the difference between event bubbling and event capturing?

bubbling: event firing first on the innermost element targeted. then successively more nested elements.

event capture is disable by default. To enable it you have to pass the caputure option in addEventListener()
