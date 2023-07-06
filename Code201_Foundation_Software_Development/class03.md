# Class 03 HTML Lists, Control Flow with JS, and the CSS Box Model.

## Question & Answer section

### Learn HTML : Ordered and Unordered lists.

* When should you use an unordered list in your HTML document?

* How do you change the bullet style of unordered list items?
    using list-line-type property to none in css .

* When should you use an ordered list vs an unorder list in your HTML document?
    order list is use for an certain order of content that we need. for example from 1 to 10. 4 to 7. or roman numerical system. 

    unorder list, in constrast, dont need any order to display content, content in which indepent from each other or dont need order to understand a certain concept.

* Describe two ways you can change the numbers on list items provided by an ordered list?

` <ol type="i">
  <li>Introduction</li>
  <li>List of Grievances</li>
  <li>Conclusion</li>
 </ol>
 `

This method will display list in roman numerical list.

` <ol start="4">
  <li>Speedwalk Stu</li>
  <li>Saunterin' Sam</li>
  <li>Slowpoke Rodriguez</li>
</ol>
`

This method will display list number start from 4.

### Learn CSS
#### The Box Model

Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

Padding box: The padding sits around the content as white space; size it using padding and related properties.


Border box: The border box wraps the content and any padding; size it using border and related properties.


[the pictures explain](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model/box-model.png)

List and describe the four parts of an HTML elements box as referred to by the box model.

margin, border, padding, content.

### Learn Js
#### Arrays. Operators and Expressions. Conditionals. Loops.

* What data types can you store inside of an Array?

Any type

* Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

yes it is a valid JavaScript array.

you can  access the values stored by syntax ` arrayName[indices]`

for example ` console.log(people[1])`

result will display another array which has pete, 32 , librarian. null





` const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]]; `


* List five shorthand operators for assignment in javascript and describe what they do.

Additional, Subtract, multpliple, division, Reminder


*Read the code below and evaluate the last expression and explain what the result would be and why.



 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;


it gonna return a string of '10dog'. In particular, false gonna return as 0 in additional operator. inwhich `(a+c) = 10+0 =0 `

then number plus string, javaScript will automaticaally transfer datatype from number to string. 

thus the result. 

 
* Describe a real world example of when a conditional statement should be used in a JavaScript program.

measure height in a class.


Give an example of when a Loop is useful in JavaScript.

loop is use for checking a certain value in an array. 
check a correct mark in a class. 
etc


