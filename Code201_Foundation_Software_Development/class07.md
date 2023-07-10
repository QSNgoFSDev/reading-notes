# Object-Oriented Programming, HTML Tables


## Domain Modeling

* Explain why we need domain modeling.

Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.



When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.

Model its attributes with a constructor function that defines and initializes properties.

Model its behaviors with small methods that focus on doing one job well.

Create instances using the new keyword followed by a call to a constructor function.

Store the newly created object in a variable so you can access its properties and methods from outside.
Use the this variable within methods so you can access the object's properties and methods from inside.

# HTML Table Basics

* Why should tables not be used for page layouts?
    table its self designed for tabular Data. 

    1. Layout tables reduce accessibility for visually impaired users: screen reader for blind ppl cant read the layour

    2. Tables produce tag soup: As mentioned above, table layouts generally involve more complex markup structures than proper layout techniques. This can result in the code being harder to write, maintain, and debug.

    3. Tables are not automatically responsive: size are default by content, not inherit by proper page layout. need extra work on css etc.

* List and describe 3 different semantic HTML elements used in an HTML <table>.

tr = table row
td = table data
th = table header


##Introducing Constructors

* What is a constructor and what 
are some advantages to using it?

Due to using object literals create only one object, what if we have to create multiple object with the same template. same properties, methods. just different in value

So constructors helps us with using 1 tempplate, and then put your new value in every single object in, the constructor will automatically fill in value with your bult template.





* How does the term this differ when used in an object literal versus when used in a constructor?

object literal only discribe a object, lets say its defined. just like a Audi Car. its brand is Audi. 

while talking about constructor function, is your works of creating object template. To me, its more like a whole factory, with same template can produce car. so if we need an audi. that factory will produce an audi. mercs, larboghi etc.




## Object Prototypes Using A Constructor


* Explain prototypes and inheritance via an analogy from your previous work experience.

as my mention example above, in explaining object literal and constructor.

we can have a conclusion such: prototypes and inheritance work in a similar way. Prototypes serve as templates or blueprints for creating new objects, while inheritance allows classes to inherit properties and methods from a parent class, enabling code reuse and promoting modular design.


* NOTE: This is a very common front end developer interview question

Bookmark and Review
## HTML Table Advanced Features and Accessibility

