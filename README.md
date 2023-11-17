# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks. 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results. 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

    `.map` performs an operation on each element in an array, populates a new array with the return value of the opperation ran on each element and then returns the new array.
    A use case example would be when we need a new array of values derived from the values of another array but want to maintain the integrtiy of the original

    `.reduce` performs an operation on each element in order, after the operation is performed on an element the return value is stored and then used in the next operation and then the final stored value is returned.
    A use case example would be when you need the sum of all numbers in an array.

    `.filter` preforms a test on each element in an array and creates a new array with only the elements that passed the test. An obvious difference from `.map` would be that the size of the array is only going to be as long as the number of elements that passed test but a not so obvious difference is that the properties of the new array are pass-by-reference, meaning they reference the same objects in memory and if the value of those objects are changed they will change in both arrays.
    A use case example would be when you need elements from an array that fit a specific criteria

2. Explain the difference between a callback and a higher order function.

    A "callback function" is a fucntion that is passed to another function as a parameter.
    A "higher order function" is a function that accepts a function as a parameter.

3. Explain what a closure is.

    In JS, a closure is the protected inner part of a function that prevents referencing of the items inside of that function by items outside of the function, without referencing the function first.

4. Describe the four principles of the 'this' keyword.

    1. Window/Global Object Binding: The default global scope binding
    2. Implicit Binding: When 'this' refers to the object calling it
    3. New Binding: When 'this' refers to a newly created instance of an object using the 'new' keyword
    4. Explicit Binding: When we explicitly bind 'this' to an object using a method ex .call()

5. Why do we need super() in an extended class?

    It calls the parent's constructor function and adds it's contents to the child

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Go into canvas and connect your repo to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/master; your codegrade score will update each time you make a push.


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
 
 [Sprint Challenge Study Guide](https://www.notion.so/bloomtech/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://bloomtech.notion.site/bloomtech/BloomTech-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) (see part 2, submitting an assignment with codegrade).
