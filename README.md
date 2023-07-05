# Reading Notes
Description: this website is to note each Lab whats learner have learned through out the course.
![The software picture is here](https://www.google.com/search?rlz=1C1VDKB_enVN1039VN1040&sxsrf=AB5stBjHnY8IvcfVS7UFNcjjOLcKbBtlQQ:1688459096179&q=software+engineer&tbm=isch&sa=X&ved=2ahUKEwjd1pSl0PT_AhWr-TgGHZg-DKYQ0pQJegQIDRAB&biw=1440&bih=809&dpr=1.5#imgrc=qHeS79kEmbJ7LM)

[Roadmap to become software engineer](https://roadmap.sh/full-stack)

Progress so far:
- [x] Intro github
- [ ] Code 201 - Foundations of Software Development. :eye_speech_bubble: :eye_speech_bubble:
- [x] Growth-mindset
- [ ] Code 301 - Intermediate Software Development.
- [ ] Code 401 - Advanced Software Development.

## Code 201 - Foundations of Software Development.
  ### Reading 1 : 
      * Compose a short poem describing how HTTP sends data between computers?
        
        
      * Describe how HTML, CSS, and JS files are “parsed” in the browser ?
      
      * How can you find images to add to a Website?
        Open imgae in new tab, in Html file, using img tag to push url of img in
      * How do you create a String vs a Number in JavaScript?
        Create a variable and attached string value like ` let var = 'String value' `
        Number is declearing number = (number value) ` let varNumber = 12345 `
        
      * What is a Variable and why are they important in JavaScript?
      
        Variable is to set a certain value to a know variable exits, to store data for later use?

      * What is an HTML attribute?

      Html attribute is stand right behind tag element. add more INFORNMATION for attribute
        
      * Describe the Anatomy of an HTMl element?
        Html element has open and closing tag with content stand between.
      
      * What is the Difference between <article> and <section> element tags?
        Where article can independtly content to distributed in website suchas newspaper artical.
        while section is a part of website usually comes with heading.
      
      * What Elements does a “typical” website include?

      Head. body. main. header. footer.
      
      * How does metadata influence Search Engine Optimization?

      understanding the topic of your web pages and content.
      
      
      * How is the <meta> HTML tag used when specifying metadata

      specify : character set, page discripton, keywords, author, document, viewport
      

      * How to start to design a Website.

      
      
      * What is the first step to designing a Website?
        Get to know your goal and objectives.
      * What is the most important question to answer when designing a Website?
      Semantics.
      
      
      
      * Why should you use an <h1> element over a <span> element to display a top level heading?
      
      * What are the benefits of using semantic tags in our HTML?
      better organize and structure language.

      
      * What is JavaScript?

      scripting language help you to create dynamic updating content
      
      * Describe 2 things that require JavaScript in the Browser?

      dropbox,
      button,
      
      * How can you add JavaScript to an HTML document?
      Write  the tag `script src `inside html to link to external js file.

  ### read 2: Introduction To Web Development
  Why is it important to use semantic elements in our HTML?
  accessibility : provide meaning and structure for the web
  
  Maintaining and read-abilty: by using elements, provided a clear structures to your pages, help others developers easy to see.
  
  
  
  Maintainability and readability: Semantic elements make your HTML code more readable and easier to maintain. By using elements like <header>, <nav>, <main>, <section>, <article>, and <footer>, you provide a clear structure to your page, which makes it easier for developers to understand and modify the code in the future. Semantic elements also enhance the overall organization and maintainability of your codebase
  
  
  
  Future-proofing: HTML evolves over time, and new elements are introduced to better represent the structure of web content. By adopting semantic elements, you ensure that your code aligns with modern web standards and practices. This makes it easier to incorporate new features and functionality into your website as the web continues to evolve
  
  
  
  Consistency and clarity: Semantic elements provide a standard vocabulary for describing the structure of web content. When developers consistently use semantic elements, it improves the clarity and understanding of the codebase, especially when working collaboratively or handing off projects to other developers.
  
  
  
  
  How many levels of headings are there in HTML?
  6
  
  What are some uses for the <sup> and <sub> elements?
  
  
  Inline styles: Inline styles are applied directly to HTML elements using the style attribute. For example: <p style="color: blue;">This is a blue paragraph.</p>. Inline styles override external and internal stylesheets. However, it is generally recommended to avoid using inline styles for the reasons mentioned below.
  
  Internal stylesheets: Internal stylesheets are defined within the HTML document using the <style> tag in the <head> section. CSS rules written inside the <style> tag apply to the HTML elements within that document.
  
  External stylesheets: External stylesheets are separate CSS files that are linked to the HTML document using the <link> tag. The CSS rules defined in the external stylesheet can be applied to multiple HTML pages by linking to the same CSS file.
  
  Inline CSS using the style attribute: In addition to inline styles, individual HTML elements can have inline CSS using the style attribute. For example: <h1 style="color: red;">This is a red heading.</h1>. This approach is less common and often used for specific cases.
  
  
  To apply CSS to HTML, you can use various methods:
  
  Inline styles: Inline styles are applied directly to HTML elements using the style attribute. For example: <p style="color: blue;">This is a blue paragraph.</p>. Inline styles override external and internal stylesheets. However, it is generally recommended to avoid using inline styles for the reasons mentioned below.
  
  Internal stylesheets: Internal stylesheets are defined within the HTML document using the <style> tag in the <head> section. CSS rules written inside the <style> tag apply to the HTML elements within that document.
  
  External stylesheets: External stylesheets are separate CSS files that are linked to the HTML document using the <link> tag. The CSS rules defined in the external stylesheet can be applied to multiple HTML pages by linking to the same CSS file.
  
  Inline CSS using the style attribute: In addition to inline styles, individual HTML elements can have inline CSS using the style attribute. For example: <h1 style="color: red;">This is a red heading.</h1>. This approach is less common and often used for specific cases.
  
  Now, let's review the code block you provided:
  
  htmlCopy code
  <p class="highlight" id="paragraph">This is a paragraph.</p>
  In this code block:
  
  The selector is the combination of the class and ID attributes, i.e., .highlight and #paragraph.The CSS declarations are the properties and values that define the styling. However, the code block you provided does not contain any CSS declarations.The properties in CSS declarations define the specific aspects of the styling, such as color, font-size, background-color, etc. In this code block, there are no properties present.
  Please note that for a complete understanding and application of CSS, you would need to provide the relevant CSS declarations and properties in addition to the HTML code.
  
  
  
  
  When using the <abbr> element, what attribute must be added to provide the full expansion of the term?
  
  CSS (Cascading Style Sheets) is structured using selectors, declarations, and properties. Let's address your questions:
  
  Ways to apply CSS to HTML:
  
  Inline styles: Applying styles directly to HTML elements using the style attribute.
  Internal stylesheets: Defining styles within the HTML document using the <style> tag in the <head> section.
  External stylesheets: Creating a separate CSS file and linking it to the HTML document using the <link> tag.
  Why avoid using inline styles:
  
  Decreased maintainability: Inline styles make it harder to manage and update styles across multiple elements since each element has its own inline style.
  Poor separation of concerns: Inline styles mix presentation with content, violating the principle of separating structure and style.
  Specificity and overriding: Inline styles have high specificity, making it difficult to override them with external or internal stylesheets.
  Now, let's review the code block you provided:
  
  htmlCopy code
  <p class="highlight" id="paragraph">This is a paragraph.</p>
  In this code block:
  
  The selector is represented by the class attribute (highlight) and the id attribute (paragraph).
  Since the code block doesn't include any CSS declarations, there are no components representing CSS declarations.
  Similarly, since there are no CSS declarations, there are no components representing properties.
  
      

      
        
## Code 301 - Intermediate Software Development.
## Code 401 - Advanced Software Development.
