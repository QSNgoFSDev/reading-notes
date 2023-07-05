# read 2: Introduction To Web Development
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
