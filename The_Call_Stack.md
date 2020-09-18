# Readings: The Call Stack and Debugging


## Call Stack
(MDN)
A call stack can only do one thing at a time.
Code execution is synchronous.
A stack frame stores temporary memory by a function invocation.

A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function, etc.
•	When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.
•	Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.
•	When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.
•	If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.

The call stack is used for invocating functions. 
The last function that gets pushed into the stack, is the first to be set off. 
The call stack maintains a record of the position of each stack frame. 

## Stack Overflow

A stack overflow is when a function call is nested within itself and will run until it hits its maximum exceeded call size set by the browser. 

## Error Messages & Debugging

1. Uncaught ReferenceError: = This means a let, const or var is undeclared. 
2.  Uncaught SyntaxError = This occurs when you have something that cannot be   parsed in terms of syntax.
3. Uncaught RangeError = This occurs when giving an object an invalid length. 
4. TypeError = This occurs when trying to use or access  a number, string, etc. that is incompatible. 

Best practice is to console log what you are trying to determine is the problem. 

MAC = (press cmd  + o ) and choose the file and line you want to debug. and refresh page. 

Place the word debugger at the end of the line you want to debug and it will break at that line. 

Or use a TRY, CATCH in js and console.error.('string', error)
