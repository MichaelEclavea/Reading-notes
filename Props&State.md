# Props and State

1. Does a deployed React application require a server?
- You are able to render the React application on your local machine, but if you wanted to render it for clients on the web, then yes.  

2. Why do we prefer to test a React application at the behavior rather than the unit level?
- Because of the nature of React, we test to see if one piece works by its counterpart. How a component is just a piece it needs to be connected to see if it actually works. 

3. What does npm run build do?
- Creates a build directory with a production build of your app. 

4. Describe the actual composition / architecture of a React application.
- first we have components, example(Header.jsx, Main.jsx, Footer.jsx, and App.jsx). We connect each child component to the App.jsx, which is the housing for each child component. The App.jsx is then placed into the index.js. The index.js is the medium between the front end and the back end. It connects the two. The index.js then renders all the combined pieces, which is the App.jsx to the index.html. 

## Vocabulary Terms: 

- BDD: behavior-driven development (BDD) is an Agile software development process that encourages collaboration among developers, QA and non-technical or business participants in a software project. [Source](https://en.wikipedia.org/wiki/Behavior-driven_development#:~:text=In%20software%20engineering%2C%20behavior%2Ddriven,participants%20in%20a%20software%20project.&text=The%20tools%20serve%20to%20add,a%20central%20theme%20of%20BDD.)

- Acceptance Tests: Formal testing with respect to user needs, requirements, and business processes conducted to determine whether a system satisfies the acceptance criteria and to enable the user, customers or other authorized entity to determine whether to accept the system.
[Source](https://en.wikipedia.org/wiki/Acceptance_testing#:~:text=In%20software%20testing%2C%20the%20ISTQB,whether%20to%20accept%20the%20system.)

- Mounting: is a process by which the operating system makes files and directories on a storage device (such as hard drive, CD-ROM, or network share) available for users to access via the computer's file system. [Source](https://en.wikipedia.org/wiki/Mount_(computing)#:~:text=Mounting%20is%20a%20process%20by,via%20the%20computer's%20file%20system.) 

- Build: refers to the process that converts files and other assets under the developers' responsibility into a software product in its final or consumable form. [Source](https://www.agilealliance.org/glossary/automated-build/#:~:text=In%20the%20context%20of%20software,(such%20as%20jar%2C%20zip))