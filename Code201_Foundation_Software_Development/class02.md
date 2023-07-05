# read 2: Introduction To Web Development

## HTML Text Fundamentals. HTML Advanced Text Formatting.
* Why is it important to use semantic elements in our HTML?
  
  accessibility : provide meaning and structure for the web
  
  Maintainability and readability: Semantic elements make your HTML code more readable and easier to maintain. By using elements like `<header>, <nav>, <main>, <section>, <article>, and <footer>,` you provide a clear structure to your page, which makes it easier for developers to understand and modify the code in the future. Semantic elements also enhance the overall organization and maintainability of your codebase
  
  Future-proofing: HTML evolves over time, and new elements are introduced to better represent the structure of web content. By adopting semantic elements, you ensure that your code aligns with modern web standards and practices. This makes it easier to incorporate new features and functionality into your website as the web continues to evolve
  
  Consistency and clarity: Semantic elements provide a standard vocabulary for describing the structure of web content. When developers consistently use semantic elements, it improves the clarity and understanding of the codebase, especially when working collaboratively or handing off projects to other developers.
  
  
  
  
* How many levels of headings are there in HTML?
  6
  
* What are some uses for the `<sup>` and` <sub> `elements?

* When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?

title attribute to add full expansion

*What are ways we can apply CSS to our HTML?
  
  To apply CSS to HTML, you can use various methods:
  
  Inline styles: Inline styles are applied directly to HTML elements using the style attribute. For example:` <p style="color: blue;">`This is a blue paragraph.`</p>`. Inline styles override external and internal stylesheets. However, it is generally recommended to avoid using inline styles for the reasons mentioned below.
  
  Internal stylesheets: Internal stylesheets are defined within the HTML document using the` <style>` tag in the `<head> section`. CSS rules written inside the `<style>` tag apply to the` HTML` elements within that document.
  
  External stylesheets: External stylesheets are separate CSS files that are linked to the HTML document using the` <link>` tag. The CSS rules defined in the external stylesheet can be applied to multiple HTML pages by linking to the same CSS file.
  
  Inline CSS using the style attribute: In addition to inline styles, individual HTML elements can have inline CSS using the style attribute. For example:` <h1 style="color: red;">`This is a red heading.`</h1>`. This approach is less common and often used for specific cases.

`h2 {
     color: black;
     padding: 5px;
   }`

* What is representing the selector? 
h2

* Which components are the CSS declarations?

Color
padding

*Which components are considered properties?

color
Padding




  



  ## Learn JS

  *What data type is a sequence of text enclosed in single quote marks?

  String

* List 4 types of JavaScript operators.

  Assignment Operators, Logical, String ,Type.

*Describe a real world Problem you could solve with a Function. 

  Random generator, BMI calculator.

## Making Decisions In Your Code – Conditionals.

An if statement checks a CONDITION and if it evaluates to TRUE , then the code block will execute.

* What is the use of an else if?

If code block of if return false, then will consider the next case is else if. if else if false, then code will fall through the rest of cases.

*List 3 different types of comparison operators. 

`>,<, =`

*What is the difference between the logical operator && and ||?

`&&` is 'and' condition, which mean code block only execute at stage both condtion is true.

`||` is 'or' condition, which mean code block execute when one out of 2 condition is true. only stop executing code block when both condition is false. 




