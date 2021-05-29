#simple interest calculator
PROGRAMS 
Build a Calculator using JavaScript, HTML and CSS in 2021
Rohan Vats  by Rohan Vats
JAN 2, 2021
Home > Software Development > Build a Calculator using JavaScript, HTML and CSS in 2021
Whether you are learning a new programming language or a development framework, there comes a time when you have to work on real-world projects. As you are advancing through the subject, you should test your skills and understanding of the language. Building a project using newly learned technology or framework is a good idea. There are plenty of ideas available online as to what you should create with your knowledge.

The most commonly found suggestions include a Calculator in JavaScript and To-do List. While they seem easy, it can be quite a task when you start working on these projects. Here, we are going to make it easy and logical as well as eventful for you. 

Shall we get started?

Learn to build applications like Swiggy, Quora, IMDB and more
Logic Before Everything Else
When you start working on a project, whether it is a calculator or a to-do list, the first thing you need to identify is the logic.

How does the calculator work?
You add two or more numbers (any number of digits) using the number keys given on the calculator.
You then perform fundamental arithmetic functions, i.e. addition, subtraction, multiplication and division on these numbers.
The calculator should be able to calculate and give out the correct solutions.
This is the premise of your calculator tool. So you need a keypad, a display unit and function elements. 

The “equals to” button will evaluate the answer while the “clear” button will ensure the removal of all the inputs on the calculator display. 


Tackling the Project: Key to Building the Code
Instead of heading to the code right away, you need to learn how to tackle a new project. You have two things ready for you: the logic and a basic understanding of the front-end technologies, i.e. JavaScript, HTML, and CSS. 

Before you begin building your calculator using JavaScript, you need the following:

An Integrated Development Environment that will help you build your project using all three technologies. 
A local server that will help you test your codes and remove the bugs. As a result, you will be able to launch the application faster and with greater agility. 
#1 Getting Started with HTML
The first step is to get your hands a bit dirty with HTML so that you have built the outline for your calculator. 

There are ten buttons on the calculator, ranging from 0 to 9. HTML is responsible for building the keys for each digit.

Apart from this, you will need to use HTML to create separate keys for the different arithmetic functions as well when building a calculator using JavaScript.

You can use HTML to add the button to display the entered digits or the results as well as to clear the display.

The visual unit of your calculator is entirely dependent on HTML and CSS, of which the buttons and their IDs need to be created using HTML.

 The Boilerplate Code

<!DOCTYPE html>

<html lang=”en”>

<head>

  <meta charset=”UTF-8″>

  <meta name=”viewport” content=”width=device-width, initial-scale=1.0″>

  <link rel=”stylesheet” type=”text/css” href=”css/styles.css”>

  <title>Calculator</title>

</head>

<body>

The Actual Code for Creating the Calculator Outline

(

  <!– calculator –>

  <div class=”calculator”>

 

    <!– display –>

    <input type=”text” class=”display” disabled>

    <!– keys –>

    <div class=”keys”>

      <!– 4 rows of keys –>

      <div class=”row”>

        <button value=”7″>7</button>

        <button value=”8″>8</button>

        <button value=”9″>9</button>

        <button value=”+” class=”operator”>+</button>

      </div>

      <div class=”row”>

        <button value=”4″>4</button>

        <button value=”5″>5</button>

        <button value=”6″>6</button>

        <button value=”-” class=”operator”>-</button>

      </div>

      <div class=”row”>

        <button value=”1″>1</button>

        <button value=”2″>2</button>

        <button value=”3″>3</button>

        <button value=”*” class=”operator”>*</button>

      </div>

      <div class=”row”>

        <button value=”C” class=”operator”>C</button>

        <button value=”0″>0</button>

        <button value=”/” class=”operator”>/</button>

        <button value=”=” class=”operator”>=</button>

      </div>

    </div>

  </div>

  <!– calculator body ends –>

  <script type=”text/javascript” src=”js/script.js”></script>

</body>

</html>

Learn: Top 20 Javascript Projects in Github For Beginners

#2 Style with CSS
Once you have defined the structure for the calculator, you will use the inline CSS elements to style your calculator and make it visually appealing and easy-to-use. 

While inline CSS is excellent when it comes to designing and styling your app’s appearance, it may not be SEO friendly. Apart from this, you can also use external CSS elements by tagging them to the same root directory. You can even use internal or embedded CSS elements that are present within the <style></style> tags within the head section.

Here, we will take you through the code that you can use to style your calculator. 

(You can create variations to this code if you want.)

/* common styles */

* {

  padding: 0;

  margin: 0;

}

body {

  width: 100vw;

  height: 100vh;

  overflow: hidden;

  display: flex;

  justify-content: center;

  align-items: center;

  background-color: #222831;

  font-family: sans-serif;

}

/* common styles end */

/* calculator */

.calculator {

  width: 300px;

  padding-bottom: 15px;

  border-radius: 7px;

  background-color: #000;

  box-shadow: 5px 8px 8px -2px rgba(0, 0, 0, 0.61);

}

/* calculator style end */

/* display */

.display {

  width: 100%;

  height: 80px;

  border: none;

  box-sizing: border-box;

  padding: 10px;

  font-size: 2rem;

  background-color: #00ff44;

  color: #000;

  text-align: right;

 border-top-left-radius: 7px;

 border-top-right-radius: 7px;

}

/* display style end */

/* row */

.row {

  display: flex;

  justify-content: space-between;

}

/* row style end */

/* button */

button {

  width: 50px;

  height: 50px;

  border-radius: 50%;

  border: none;

  outline: none;

  font-size: 1.5rem;

  background-color: #222;

  color: #fff;

  margin: 10px;

}

button:hover {

  cursor: pointer;

}

/* button style end */

/* operator */

.operator {

  background-color: #00ff44;

  color: #000;

}

/* operator style end */
