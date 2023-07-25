# Readings: Chart.js, Canvas
Below you will find some reading material, code samples, and some additional resources that support the topic for this class and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

Reading
## JavaScript Canvas

- [x] What does the <canvas> allow a developer to acheive?
- [x] 
 is an element that allows you to draw 2D graphics using JavaScript

- [x] What is the importance of the closing `</canvas> tag?

Closing tag so they can have a fall back content between open canvas and closed canvas tag. It will display only if the brwoser dosnt support the canvas element


- [x] Explain what the getContext() method does.

getContext() method that returns a render context object. (size,fill,stroke) 

fir example: `
let canvas = document.querySelector('#canvas');
let ctx = main.getContext('2d');
`



## Chart.js Documentation:

- [x] What is Chart.js and how it can be brought into your project?

Is a chart library for JS. 



- [ ] List 3 different Chart types you can create using Chart.js.
  * line chart
  * pie chart
  * bar chart

- [ ] Easily Create Stunning Animated Charts with Chart.js

- [ ] What are some advantages to displaying data via a chart over a table?

Visually access and valuate the situation and status of the data present in the table. highlight key performance. 


- [ ] How could Chart.js aid your previously created applications visually?

Chartjs will immidiately tracking visually for user which one got the highest vote without needed to  calculate or remember which one used to have the highest vote. 

it represent right in the chart.