# HTTP & REST

# HTTP and REST

1. Define three related pieces of data in a possible application. An example for a store application might be Product, Category and Department. Describe the constraints and rules on each piece of data and how you would relate these pieces to each other. For example, each Product has a Category and belongs in a Department.
 - Example being product review. 
    name of product
    category
    product rating


2. What is the advantage of an ORM, like Mongoose?
	It interacts with the main code as objects.

3. How does the repository pattern compare with an ORM?
	Repositories deal with Domain/Business objects (from the app point of view), an ORM handles db objects. A business objects IS NOT a db object, first has 	behavior, the second is a glorified DTO, it only holds data. Source: https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwj5yeKRjsHsAhVYoZ4KHRwMBhoQFjABegQIBhAC&url=https%3A%2F%2Fstackoverflow.com%2Fquestions%2F10155517%2Frepository-pattern-vs-orm&usg=AOvVaw2SrCr_WvtRTNUP8ZCOk1WL
	
4. When making a repository/facade, what flexibility do you gain?
easy data manipulation when wanting to change data storage. 

5. Name 3 cloud based NoSQL Databases
MongoDB Atlas, Microsoft Azure,  Amazon Dynamo

## Vocabulary Terms: 

1. lifecycle: Stages data information goes through from start, to finish. 6 total stages.

2. Collections: non-relational  collection of data storage

3. the "Repository" design pattern: 

4. mongoose middleware: is a response and request middleware between database and client

5. Object Relation Mapping (ORM): The method of interacting or communicating between incompatible type systems. 
