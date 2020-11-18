# Component Composition

1. Can a parent component access the state of a child component?
- Yes. One answer would be a callback function. 

2. What can be passed along in a prop variable?
- Things that can be passed along are variables, arrays, objects, etc.

3. How can a child component “know” the state of another component? Can a parent component access the state of a child component?
- Yes a child component can. By a component using state, it then can pass that information through props and the child can use this.props.(whatever). 


## Vocabulary Terms:

- Component Props:  are arguments passed into React components. Props are passed to components via HTML attributes. [Source](https://www.w3schools.com/react/react_props.asp)

- Component State: is an object that contains information that may or may not change over the lifecycle of a component. State object stores values of properties related to a component. [Source](https://www.educba.com/react-state-vs-props/#:~:text=The%20state%20of%20a%20react,properties%20related%20to%20a%20component.)

- Application State: The "state" of a program at a given time refers to a snapshot of all the data the program is currently looking at or analyzing to get to the next step in it's execution. My university started with Scheme, so we started programming with a state-less model. [Source](https://softwareengineering.stackexchange.com/questions/150120/definition-of-state#:~:text=The%20%22state%22%20of%20a%20program,with%20a%20state%2Dless%20model.)