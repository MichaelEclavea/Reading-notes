
# Express

1. What is the difference between PUT and PATCH? 

- PUT is supplies a modified version, which replaces the entire original version. 

- PATCH only modifies the original source. 

2. Provide links to 3 services or tools that allow you to "mock" an API for development like json-server.

- NOCK: https://github.com/nock/nock
- MockServer: http://www.mock-server.com/
- Beeceptor: https://beeceptor.com/

3. Compare and contrast Swagger and APIDoc.js 1 which HTTP status codes should be sent with each type of (un)successful API call? 

- 200: OK
- 400: Bad request
- 401: Authorization is missing or invalid
- 404: Not found
- 500: unexpected error

4. Compare and contrast SOAP and REST.
- SOAP is a standardized protocol that sends messages using other protocols such as HTTP and SMTP. ... It allows different messaging formats, such as HTML, JSON, XML, and plain text, while SOAP only allows XML. REST is also a more lightweight architecture, so RESTful web services have a better performance

Source: https://raygun.com/blog/soap-vs-rest-vs-json/#:~:text=SOAP%20is%20a%20standardized%20protocol,such%20as%20HTTP%20and%20SMTP.&text=It%20allows%20different%20messaging%20formats,services%20have%20a%20better%20performance.


## Vocabulary Terms: 

1. SOAP: is a messaging protocol specification for exchanging structured information in the implementation of web services in computer networks.

2. ReST Verbs: is a software architectural style that defines a set of constraints to be used for creating Web services.

3. CRUD Verbs: The primary or most-commonly-used HTTP verbs (or methods, as they are properly called) are POST, GET, PUT, PATCH, and DELETE. These correspond to create, read, update, and delete (or CRUD) operations, respectively. There are a number of other verbs, too, but are utilized less frequently.

4. Swagger: is a powerful yet easy-to-use suite of API developer tools for teams and individuals, enabling development across the entire API lifecycle, from design and documentation, to test and deployment. 
