# Express Routing & Connected API

1. Name 3 real world use cases where you’d want to change the request with custom middleware

- One would be to check if the user is logged in and verified to continue, logging data and analytics.

2. True or False: The route handler is middleware? 

- True.

3. In what ways can a middleware function end the process and send data to the browser? 

- res.send() and res.end().

4. At what point in the request lifecycle can you “inject” middleware?

- after the route being hit first 

5. What can cause express to error with “Request headers sent twice, cannot start a second response”

- It is possible to get a double error if there was a loop that the server was in and spitting out the errors. 


## Vocabulary Terms

1. Middleware:  is software that lies between an operating system and the applications running on it.

2. Request Object: is used with the Alpha Anywhere Standard Application Server. ... This object represents the parsed HTTP request that was received by the Application Server and has a number of properties available.

3. Response Object: is used with the Alpha Anywhere Standard Application Server. ... This object represents the HTTP response that will be created by the Application Server and sent back to the client.

4. Application Middleware: is computer software that provides services to software applications beyond those available from the operating system.

5. Routing Middleware: is software or hardware infrastructure supporting sending and receiving messages between distributed systems.

