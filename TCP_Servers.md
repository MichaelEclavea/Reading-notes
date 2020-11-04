# TCP Servers

1. Given the examples of front-end events such as button click, window resize, form submit, etc, what are some examples of back-end events?
- onclick, onmouseover, keydown, keyup, keypress, etc. 

2. Why are events sometimes better than asynchronous actions with callbacks?
- because events trigger the action, which might never happen. With async functions & callbacks, it is constantly running. The event triggers the event function while the callback function is running at all times. 

3. What does an EventEmitter instance do?
- allows us to create a custom event.

4. When is a program’s call stack, event queue, and event loop active?
-  when there are data to process. 


## Vocabulary Terms

- Observer Pattern: The observer pattern is a software design pattern in which an object, called the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.
[Source](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwi4vK6GpOjsAhXEu54KHSNEBJ0QFjAGegQIChAC&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FObserver_pattern&usg=AOvVaw0CPdsmiZCtU8Ieqf7LxIQn).

- Listener: is a procedure or function in a computer program that waits for an event to occur. ... The listener is programmed to react to an input or signal by calling the event's handler. The term event listener is often specific to Java and JavaScript.
[Source](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiPqMOjpOjsAhXHsJ4KHWKOB14QFjABegQIBhAC&url=https%3A%2F%2Fwww.computerhope.com%2Fjargon%2Fe%2Fevent-listener.htm&usg=AOvVaw0LW0gDbhJgfcPI6wwl5KNy)

- Event Handler: is a callback subroutine that handles inputs received in a program (called a listener in Java and JavaScript).
[Source](https://en.wikipedia.org/wiki/Event_(computing)#Event_handler)

- Event Driven Programming:  is a programming paradigm in which the flow of the program is determined by events such as user actions (mouse clicks, key presses), sensor outputs, or messages from other programs or threads.
[Source](https://en.wikipedia.org/wiki/Event-driven_programming)

- Event Loop: A programming structure that continually tests for external events and calls the appropriate routines to handle them. An event loop is often the main loop in a program that typically waits for the user to trigger something.
[Source](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwi-gd2ppejsAhXPup4KHV6UBjYQFjABegQIBhAC&url=https%3A%2F%2Fencyclopedia2.thefreedictionary.com%2Fevent%2Bloop&usg=AOvVaw2mbLrmcCIE-NSdDkVwgPvS)

- Event Queue:  is a repository where events from an application are held prior to being processed by a receiving program or system. Event queues are often used in the context of an enterprise messaging system. [Source](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwinjNjApejsAhWGup4KHXQwDnkQFjABegQIBhAC&url=https%3A%2F%2Fwww.techopedia.com%2Fdefinition%2F24963%2Fevent-queue&usg=AOvVaw00XZ9r8YhmshbT437XjBG-)

- Call Stack: is a stack data structure that stores information about the active subroutines of a computer program. [Source](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjLjqnYpejsAhXYpJ4KHcrJC3UQFjABegQIBRAC&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FCall_stack&usg=AOvVaw1REJNJksOHe-DVi6zuWOsQ)

- Emit/Raise/Trigger: is an emitter sends out a certain event for a method that is listening to it. 

- Subscribe: is a messaging pattern where senders of messages, called publishers, do not program the messages to be sent directly to specific receivers, called subscribers, but instead categorize published messages into classes without knowledge of which subscribers, if any, there may be. [Source](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjEpN-ApujsAhXJr54KHX-JDzUQFjABegQIBhAC&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FPublish%25E2%2580%2593subscribe_pattern&usg=AOvVaw0YqMt7NX_xMQSB6_67Ux4I)

- database: is a program whose primary purpose is entering and retrieving information from a computerized database. A database application facilitate simultaneous updates and queries from multiple users. [Source](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwi89PeopujsAhUHpZ4KHYsxA24QFjABegQIBRAC&url=http%3A%2F%2Fwww.tsspltd.com%2Fservices%2Fdatabase-application-development.html&usg=AOvVaw2Epcy3MB8__OsebbIJbfXh)