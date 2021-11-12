# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

.map() ---> Returns a new array, calls back each element, index and returns each in turn. You would use it when manipulating/reshaping data: when you are given data and you need to do something to change it WITHOUT altering the original array.

.reduce() ----> Returns a new array, takes a callback which is a reducer function, reducer function takes previous value (accumulator) and next value (currentValue). Biggest feature is that .reduce() returns a single value. You would use it when you have a big dataset and want to turn it into a single piece of data (ex: average, sum, etc.).

.filter() ----> Returns a new array, calls back each element, index and returns each in turn. It takes a callback that runs a 'truth' test: if true, returns the elements, else ignores. You would use it for filtering out an array by a specific condition (ex: when you only want names that start with an 'a').

2. Explain the difference between a callback and a higher order function.

A higher order function is a function that accepts other functions as its arguments. 
A callback function is a function that is passed into other functions as an argument.

3. Explain what a closure is.

Closure happens when a function is referencing some sort of variable outside of its context. It is the ability to access functions from a parent level scope in child level scope even after the parent function has been terminated. 

4. Describe the four principles of the 'this' keyword.

  - Window/Global Object binding - when in global scope, the value of 'this' will be the window or console object (in this case, 'this' is without context)
  
  - Implicit Binding - whenever a preceding dot calls a function, the object before the dot is 'this'
  
  - New Binding - when a function is invoked as a constructor function, 'this' points to the newly created object (whenever a constructor function is used, 'this' refers to the specific instance of the object that is created and returned by teh constructor function)
  
  - Explicit Binding- when we explicitly pass in what we want 'this' to refer to using .call, .apply, .bind

5. Why do we need super() in an extended class?

It tells a parent's constructor to be concerned with the child's attributes and abstracts away the 'Object.create(this,Class)' syntax that is harder to understand.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Go into canvas and connect your reop to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/ master your codegrade score will update each time you make a push.


### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://lambdaschool.notion.site/lambdaschool/Lambda-School-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) See part 2, submitting an assignment with codegrade
