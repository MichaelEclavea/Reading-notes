# Redux - Additional Topics

1. What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?
- useEffect

2. When using a thunk/async action that dispatches the actual action, which do you export from your reducer?
-  I am actually unsure about this answer. But I would assume it is the current state. 


### Vocabulary Terms: 

- middleware: In this case, Redux middleware function provides a medium to interact with dispatched action before they reach the reducer. ... Each middleware receives store's dispatch so that they can dispatch new action, and getState functions as arguments so that they can access the current state and return a function. [Source](https://www.tutorialspoint.com/redux/redux_middleware.htm#:~:text=In%20this%20case%2C%20Redux%20middleware,before%20they%20reach%20the%20reducer.&text=Each%20middleware%20receives%20store's%20dispatch,state%20and%20return%20a%20function.)

- thunk: Redux Thunk is a middleware that lets you call action creators that return a function instead of an action object. That function receives the store's dispatch method, which is then used to dispatch regular synchronous actions inside the function's body once the asynchronous operations have been completed. [Source](https://www.digitalocean.com/community/tutorials/redux-redux-thunk#:~:text=Redux%20Thunk%20is%20a%20middleware,asynchronous%20operations%20have%20been%20completed.)

