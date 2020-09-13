# NODE.JS (Node, Express & APIs): 

Node.js® is a JavaScript runtime built on Chrome’s V8 JavaScript engine.

Node.js is an event-based, non-blocking, asynchronous I/O runtime that uses Google’s V8 JavaScript engine and libuv library.

The V8 engine was designed with performance in mind and is responsible for compiling JavaScript directly to native machine code that your computer can execute.

This means that Node.js is a program we can use to execute JavaScript on our computers. In other words, it’s a JavaScript runtime.


To install: npm install node


How to install package globally 

Npm install -g jshint

Jshint package will be installed globally and can use it to lint files


How to install a package locally 

Npm init -y



Creating. A test.js

const _ = require('lodash');

const arr = [0, 1, false, 2, '', 3];
console.log(_.compact(arr));


The biggest use for Node.js is running javascript on the server.

The following code is how to run your server and to send a response along with the users request. 

const http = require('http');

http.createServer((request, response) => {
  response.writeHead(200);
  response.end('Hello, World!');
}).listen(3000);

console.log('Server running on http://localhost:3000');


Node.js is best suited for applications that require real time communication, where you are able to see someone editing live.

So real time applications is a great use of Node.js

A great reason for using node.js is its great compatibility with JSON. Other languages would need to reformat the JSON file, but not with node.js. Another great reason is that Node.js and Javascript speak the same language. So developers do not have to go back and forth between two languages, they can just use the one. 


Vue.js + Vue CLI – is a straightforward frontend framework. It is one of the fastest ways to bootstap a project and lets you get straight to coding. 

Svelte – is a new front-end framework that has everyone raving how easy it is to use. This framework is reactive by default. 

MongoDB + Mongoose – 
MongoDb is a general purpose, document-based, distributed database built for modern application developers and for the cloud era. 

Sails – is a model-view-controller web application framework. It simplifies the process of creating regular, modern web apps. 

Meteor is a JavaScript full-stack framework for creating both web and mobile applications. 


Three.js – This is used for building anything 3D in the browser. This is a great application to add to wow users and it is not just for games. 
