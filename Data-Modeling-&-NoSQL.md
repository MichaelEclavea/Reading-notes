# Data Modeling & NoSQL Databases

1. Name 3 advantages to test driven development.

- implementing tests before writing code, sets up the developer to know the strict behavior of the code before, during and after it is written. 

- It helps other developers outside of who wrote the code, to help guide them through the person who wrote the codes process.

- It can help with the overall quality of the written code by laying  out guidelines to follow. 

2. In what case would you need to use beforeEach() or afterEach() in a test suite? 

- afterEach will run after each test case block and beforeEach will run after each test case block. 

3. What is one downside of test driven development?

-  In a creative environment, developers cannot freely open themselves to new ideas and run with them. Instead they are bound to strict guidelines to follow and do not have that creative touch as they move through their coding process. 

4. What's the primary difference between ES6 classes and constructor/prototype classes? 

-  The most important difference between class- and prototype-based inheritance is that a class defines a type which can be instantiated at runtime, whereas a prototype is itself an object instance.

reference: Justen Robertson 
URL: https://www.toptal.com/javascript/es6-class-chaos-keeps-js-developer-up

5. Name a use case for a static method

- When you need to make multiple instances of a class. 

6. Write an example of a higher order function and describe the use case it solves.

- function greaterThan(n) {
  return m => m > n;
}
let greaterThan10 = greaterThan(10);
console.log(greaterThan10(11));


https://eloquentjavascript.net/05_higher_order.html




### Vocabulary Terms

functional programming - In computer science, functional programming is a programming paradigm where programs are constructed by applying and composing functions. Wikipedia

pure function - have no side effects (memory or I/O). This means that pure functions have several useful properties, many of which can be used to optimize the code:

higher-order function - functions that can either take other functions as arguments or return them as results.

immutable state - A state in which values, structures, or data cannot be changed

object - A representation of a real-life item or person that has properties and methods representing its features and abilities. 

object-oriented programming (OOP) -  A programming paradigm of creating applications and software based on using objects to store data in the form of attributes and properties, and code in the form of methods

class -  Special functions that are templates for creating objects in JavaScript. Built on prototypes, and encapsulate data with related code needed to work on that data

prototype - Prototypes are the mechanism by which JavaScript objects inherit features from one another. In this article, we explain how prototype chains work and look at how the prototype property can be used to add methods to existing constructors.

super - The super keyword is used to access and call functions on an object's parent.

inheritance - All JavaScript objects inherit properties and methods from a prototype, which passes them down a prototype chain

constructor - is a special method of a class for creating and initializing an object of that class.

instance - is a concrete occurrence of any object, existing usually during the runtime of a computer program.

context - It refers to the object within the function being executed



this - keyword refers to the object it belongs to.


Test Driven Development (TDD) - is a software development process that relies on the repetition of a very short development cycle: requirements are turned into very specific test cases, then the code is improved so that the tests pass.


Jest - a JavaScript testing framework designed to ensure correctness of any JavaScript codebase.

Continuous Integration (CI) - is the practice of merging all developers' working copies to a shared mainline several times a day.

unit test - A unit test runs over segments of our programs checking the input and output. These tests allow developers to check individual areas of a program to see where(and why) errors occur.

Other Sources: 

MDN DOCS - https://developer.mozilla.org/en-US/docs/Web/JavaScript

W3schools - https://www.w3schools.com/

Wikipedia - https://en.wikipedia.org/wiki/JavaScript_syntax