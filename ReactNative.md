# React Native

1. Compare and Contrast Redux Toolkit with Redux “Ducks”.
- Redux is used mostly for application state management. To summarize it, Redux maintains the state of an entire application in a single immutable state tree (object), which can't be changed directly. When something changes, a new object is created (using actions and reducers).
- Redux Ducks on the other hand, Ducks is a useful way to grow a React/Redux app with a file system that grows along with your app. It eliminates the margin for error when importing actions across multiple components and allows for more modularity. [Sources](https://medium.com/building-crowdriff/react-redux-file-architecture-ducks-it-up-6b32eaaba341). [Sources](https://www.smashingmagazine.com/2016/06/an-introduction-to-redux/).

2. What is the principle advantage of Redux Toolkit?
- This toolkit provides some useful libraries and has comfort functions to make the syntax of Redux a bit more understandable. Also the code becomes a bit more compact because default values are used for many things. The Redux Toolkit is flexible and can be combined with normal Redux without problems. [Source](https://blog.codecentric.de/en/2020/02/simplifying-redux-with-the-redux-toolkit/#:~:text=This%20toolkit%20provides%20some%20useful,with%20normal%20Redux%20without%20problems.)