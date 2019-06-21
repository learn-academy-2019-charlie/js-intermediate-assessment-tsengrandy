# Intermediate Javascript Assessments

### Without using Google answer the following:

1. What is the difference between .map() and .filter()?
.map() repeats an action on every cell in the array
.filter() will only push cells to the updated array if it satisfies a conditional

2. Why would you use object destructuring?
It makes it easier to access specific properties rather than having to type this.thing.item.characteristic.status.location.etc....

3. What is the difference between var, let, and const?
var declares a variable in the global scope
let declares a variable in the local scope
const declares a variable that is immutable and cannot be changed later on

4. Why is testing important?
It helps drive the planning process of programming such as in TDD
It helps you find edge cases of your program

5. What is a higher order function?
A higher order function is a function that either takes in a function as an argument or returns another function

6. What is the difference between a class and an object?
An object is comprised of data and behaviors
A class is a blueprint for creating objects

7. What did you learn during the group project this week? Please include any additional feedback you may have.
I learned that we all have different strengths. It was helpful to have someone have a separate skillset and perspective

### HTML/CSS Review questions: First, try to answer each question on your own then Google the answer to further your knowledge.

1. How do you link a CSS file to your HTML page?
In the head section of HTML, insert
<link rel="stylesheet" type="text/css" href="./CSSFILENAMEHERE.css">

2. What is the difference between a div and a span?
A div separates your info into blocks whereas a span is inline and will not affect the syntax of the document.

3. What is a CSS class? When should you use an id instead of a class?
A CSS class is a tag you set so you can style everything in a page with the same "className" An ID is used for specific instances and needs to be unique. It can be useful for linking to an anchor element or in JS, useful for getElementById() calls

4. Name 4 semantic HTML tags.
<p></p>
<h1></h1>
<ul></ul>
<br>

5. What are three options for creating responsive design?
Adding "alt" text
Resizing the screen for different screen sizes
Using relative sizes for images

### Stretch: The following questions are potential interview questions. First, try to answer each question on your own then Google the answer to further your knowledge.

1. What is front end development? Can you identify any tools/skills that are uniquely required of front end developers?
Coding in the front end is focused on what the user actually sees. What is shown on the screen, displayed to the user.
React, Rails, HTML, CSS, Node.js

2. What is block scope in JavaScript?
It's the local scope within a chunk of code, such as an enclosed for loop.

3. How would you explain the idea of "inheritance" in object oriented programming?
Inheritance is the flow or "inheriting" of properties and methods from a parent object to its children objects. If Car was a parent object with a wheel property of 4, then the child objects Honda and Toyota would automatically have a wheel property of 4 as well.