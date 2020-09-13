# Heroku Deployment

### View Logs

( $ heroku login ) This is to login into heroku on terminal.


Heroku treats logs as streams. This to me sounds like github with their branches. 

// heroku logs --tail     is a logging command that shows information about the running app.

// control+C       	stop streaming log


### Defining a Procfile 

Procfile – is a text file in the root of your application. 

// web: node index.js    	is a command that declares that this process type will be attached to a HTTP routing stack of Heroku.



### Scaling the App

To run an app on Heroku, uses what is call dyno hours. The free version gives you a certain amount of accesses. When ( $ Heroku ps:scale web=0 ) then you out of web dynos to serve requests and run. 

( $ Heroku ps:scale web=1 ) is to scale up your web dynos. 


### Declaring app dependencies

The package.json file in the root directory lets Heroku recognize the app as Node.js.

( npm init --yes ) creates this json file in your directory. 

( npm install ) this installs the dependencies that are needed to run your app locally. 
Make sure to check this into git after finishing. 

### How to run the app locally

( heroku local web ) This starts app locally

Open Browser:  http://localhost:5000  	This will show app running online.

Ctrl-C   	to exit.
Push local changes

( $ npm install cool-ascii-faces )  This is to propagate a local change to local app to Heroku.


### Now deploy to GitHub!

༼ つ ◕_◕ ༽つ

This is what this app creates ! 

( $ Heroku open cool ) This is to determine that everything is working .

### Provision add-ons

Papertrail is an add on that provides real time logs and alerts regarding the status of your application.

Call Papertrail ( $ heroku addons:create papertrail ) 

Show list of add ons  	( $ heroku addons )

( $ heroku addons:open papertrail ) This will let the browser open up web console and show papertrail logs. 


### Heroku Config vars

( $ heroku config ) view the config vars that are set using heroku config. 


( $ heroku config:set GITHUB_USERNAME=michaeleclavea ) setting a config var

( $ heroku config:unset GITHUB_USERNAME ) removing a config var


( $ heroku addons:create heroku-postgresql:hobby-dev ) This creates a database and sets a DATABASE_URL environment variable.

( $ npm install pg ) adds node-postgres to all our dependencies.





### Heroku Deployment: Reading 05

Node.js is an open source environment that lets you build applications for networking and server-side applications.

### How to create a server!

var http = require("http");

http.createServer(function(request, response) {
  response.writeHead(200, {"Content-Type": "text/plain"});
  response.write("It's alive!");
  response.end();
}).listen(3000);

create the js file to be names server.js

call this server in terminal in server.js

with the code above it is setting the browser to link with our server at localhost:3000


var http = require(“http”); 	 gives key to Node’s HTTP functionality.
var fs = require(“fs”); 		interaction with the file system.
var path = require(“path”);	this handles file paths.
var mime = require(“mime”);  allows us to determine the MIME-type.

Go through th install of name version and so on. 

( $ npm install ) 


### Creating a 404 function that will hand the error page of non existing file ( 404 error ).

Function send404(response) {
response.writeHead(404, {“Content-type” : “text/plain”});
response.write(“Error 404: resourse not found”);
response.end();
}




sendPage() function. This writes the header and then sends the contents of the file. 

function sendPage(response, filePath, fileContents) {
  response.writeHead(200, {"Content-type" : mime.lookup(path.basename(filePath))});
  response.end(fileContents);
}

### creating http server.

var server = http.createServer(function(request, response) {
  var filePath = false;

  if (request.url == '/') {
    filePath = "public/index.html";
  } else {
    filePath = "public" + request.url;
  }

  var absPath = "./" + filePath;
  serverWorking(response, absPath);


( $ node server.js ) command to run server locally.
});
