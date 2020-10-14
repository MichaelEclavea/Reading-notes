
# Readings: Classes, Inheritance, Functional P...

1.	Why would you want to run JavaScript code outside of a browser? 
2.	What is the difference between a module and a package?
3.	What does the node package manager do?
4.	Provide code snippets showing 3 different ways to export a function from a node module
	
	
1. To interact with the machine of the user. This would be necessary if creating an actual desktop application. 
2.  A package is a collection of modules/files wrapped together.
      A module is essentially a single js file. 
3. NPM is a JS library of open source-code for developers to or could use. 
4. 
module.exports = function (count, legs) {
  this.count = count;
  this.legs = legs;
}

const myFunction = () => {
  console.log('Hello World!');
};

exports.myFunction = myFunction;
module.exports = function (note) {
  console.log(note);
};







## Document the following Vocabulary Terms
•	ecosystem: A network of software, applications, and projects that are centered around/utilize the same programming environment. Source.
•	Node.js: An open-source JavaScript development environment that allows you to write JavaScript on the back-end of an application.
•	V8 Engine: An open-source JavaScript runtime created by Google written in C++. Powers Google Chrome browser. Source.
•	module: A JavaScript file featuring a function or set of functions you want to use in your application. Source.
•	package: A collection of modules wrapped together for developers to download and use.
•	node package manager (npm): A huge, open-source repository for software to be used in Node.js projects. Free to use and also features a command-line installation tool. Source
•	server: A piece of hardware or software that "serves" functionality to other programs known as "clients". Source.
•	environment: A workspace for developers to write and change code without affecting a live application. A base on which programming can be implemented. Source.
•	interpreter: A program that translates code from a written, human-readable programming language into machine-readable code and instructions (in binary bits). Interpreters convert the code at the time the program is run. Source.
•	compiler: A program that translates code from a written, human-readable programming language into machine-readable code and instructions (in binary bits). Compilers convert the code before the program is run. Source.


## Class Constructors

to create a class constructor - class Animal{ 
					constructor(age, weight){
						this.age = age;	
						this.weight = weight;	
					   }
						walk(){
							console.log('animal is walking...');
					}
to use another constructor to use the same values as another: 

	class Horse extends Animals{}

