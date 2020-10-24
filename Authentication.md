# Authentication

1. Explain what a “Singleton” is (in Computer Science terms) - is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. The term comes from the mathematical concept of a singleton.

2. Explain how the Singleton pattern can be used with Node modules, specifically with classes - (https://derickbailey.com/2016/03/09/creating-a-true-singleton-in-node-js-with-es6-symbols/)

3. If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it? 

- first thing will be to setup the express server. Then to create routes and define the specified user querys to the routes and there specific functions. Create error handling functions. If need be for application purposes, create application middleware. 



## Vocabulary Terms: 


1. Router Middleware: this is like app.use, instead it is app.router. This allows us to chain together the rest functions together with a single route. 

2. Dynamic Module Loading:  provide the following functions: Load, refresh, and delete installation load modules, which are not part of the IBM® base JES2 code, after JES2 initialization processing. ... Note: This function does not support base JES2 modules, so it can NOT be used to apply IBM service.
https://www.ibm.com/support/knowledgecenter/SSLTBW_2.1.0/com.ibm.zos.v2r1.hasc100/dynlodmod.htm#:~:text=Dynamic%20load%20modules%20provide%20the,code%2C%20after%20JES2%20initialization%20processing.&text=Note%3A%20This%20function%20does%20not,used%20to%20apply%20IBM%20service.

3. Singleton Pattern:  limits the number of instances of a particular object to just one. This single instance is called the singleton. Singletons are useful in situations where system-wide actions need to be coordinated from a single central place.
https://www.dofactory.com/javascript/design-patterns/singleton#:~:text=The%20Singleton%20Pattern%20limits%20the,from%20a%20single%20central%20place.

4. CRUD -> REST Method Matches: PUT = (Create and Update), Post = (Create), GET = (Read), Delete = (Deletes).

5. Mock Testing: is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. In mock testing, the dependencies are replaced with objects that simulate the behaviour of the real ones.
