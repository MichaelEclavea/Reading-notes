# Redux Combined Reducers

1. Why choose Redux instead of the Context API for global state?
- Context API is easy to is use as it has a short learning curve. It requires less code, and because there's no need of extra libraries, bundle sizes are reduced. Redux on the other hand requires adding more libraries to the application bundle. The syntax is complex and extensive creating unnecessary work and complexity. [Source](https://www.codehousegroup.com/insight-and-inspiration/tech-stream/using-redux-and-context-api)

2. What is the purpose of a reducer? are functions that take the current state and an action as arguments, and return a new state result. In other words, (state, action) => newState. [Source](https://redux.js.org/tutorials/fundamentals/part-3-state-actions-reducers#:~:text=Reducers%20are%20functions%20that%20take,%2C%20action)%20%3D%3E%20newState%20.)

3. What does an action contain? a plain JavaScript object that contains information. Actions are the only source of information for the store. Actions have a type field that tells what kind of action to perform and all other fields contain information or data. [Source](https://www.geeksforgeeks.org/introduction-to-redux-action-reducers-and-store/#:~:text=Actions%3A%20Actions%20are%20a%20plain,fields%20contain%20information%20or%20data.)

4. Why do we need to copy the state in a reducer?
It is so we have an immutable copy of state. 

## Vocabulary Terms: 

- immutable state:  is a concept that React programmers need to understand. An immutable value or object cannot be changed, so every update creates new value, leaving the old one untouched.[Source](https://blog.logrocket.com/immutability-in-react-ebe55253a1cc/)
- time travel in redux: he Redux DevTools records dispatched actions and the state of the Redux store at every point in time. ... This makes it possible to inspect the state and travel back in time to a previous application state without reloading the page or restarting the app.[Source](https://medium.com/the-web-tub/time-travel-in-react-redux-apps-using-the-redux-devtools-5e94eba5e7c0#:~:text=The%20Redux%20DevTools%20records%20dispatched,page%20or%20restarting%20the%20app.)
- action creator:  is merely a function that returns an action object. Redux includes a utility function called bindActionCreators for binding one or more action creators to the store's dispatch() function.[Source](https://read.reduxbook.com/markdown/part1/04-action-creators.html#:~:text=Chapter%20recap,the%20store's%20dispatch()%20function.)
- reducer: is a function that determines changes to an application's state. It uses the action it receives to determine this change. We have tools, like Redux, that help manage an application's state changes in a single store so that they behave consistently.[Source](https://css-tricks.com/understanding-how-reducers-are-used-in-redux/#:~:text=A%20reducer%20is%20a%20function,so%20that%20they%20behave%20consistently.)
- dispatch: is the method used to dispatch actions and trigger state changes to the store. react-redux is simply trying to give you convenient access to it. Note, however, that dispatch is not available on props if you do pass in actions to your connect function.[Source](https://stackoverflow.com/questions/42871136/dispatch-function-in-react-redux#:~:text=dispatch()%20is%20the%20method,actions%20to%20your%20connect%20function.)