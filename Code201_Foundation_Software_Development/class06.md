# Class06 : Problem Domain, Objects, and the DOM.

## JavaScript Object Basics


* How would you describe an object to a non-technical friend you grew up with?

An object is a collection of related data and/or functionality. These usually consist of several variables and functions (which are called properties and methods when they are inside object)

To a non-technical perspective. A object is like a car. a car has its own property such as paint, frame, seat. also it has a method, such as aircon, engine, steerwheel.\

object property or method always go in pairs, key : value

for such further explaination such as following code.

`
car = {
  <!-- property -->
  paint : red,
  frame : steel,
  seat : 5,

  <!-- method -->
  aircondition : function (cool the car),
  engine: function (make the car runing),
  steerwheel: function (help user drive the car),


}

`

* What are some advantages to creating object literals?
  - Simplicity and Readability: Display straight away as such property and method. key : value.
  - Flexibility: in defining and modifyign object property. can add remove ipdate property of object without creating another function or method.
  - Enhanced Object Composition: combine multiple objects into a single object literal.




* How do objects differ from arrays?
  - Structures: 
  Object are unordered key-value pairs. object allow to access value by correspoding key.
  Array are ordered, numerical indexed. Array allow to acess value based or thier indices. 
  - Iteration:
  Object Iterating over object properites requires specific methods or looping construct.
  Array: have built in methods, for example: forEach, map,reduce. make it easier to loop.


* Give an example for when you would need to use bracket notation to access an object’s property 
instead of dot notation.

If you need to access a key : value pairs with an special character or format. such as string has a space between as key,

`
const person = {
  'first name': 'John',
  'last name': 'Doe',
  'if': 'condition',
};

console.log(person['first name']); // Accessing property with a space
console.log(person['if']); // Accessing property with a reserved keyword

`

if using dot notation at this instance, it will return a syntax error. 

But in general, using dot notation give a clear a readability to your code. 


* Evaluate the code below. What does the term this refer to and what is the advantage to using this?


`
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
`

the "this" key word refer to a dog object. in which we can clearly write as: dog.name

The advantages of using this is its property: dynamic. 

This can be use to refer its current object. 

for example: 

`

const Lost = {
  name: 'Fog',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

`

This code above will return a result this.name as Fog. Since this it self replace a curerent object is Lost. it can be write. at this very instances as: Lost.name instead of this.name .

## Introduction To The DOM : Document Object Model


* What is the DOM?

The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.


* Briefly describe the relationship between the DOM and JavaScript.

JavaScript and the DOM have a symbiotic relationship. JavaScript provides the ability to manipulate the DOM, enabling dynamic and interactive web experiences, while the DOM provides the structure and content for JavaScript to interact with and modify. Together, they form a powerful combination for building web applications.


