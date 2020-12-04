# Redux - Asynchronous Actions

1. How granular should your reducers be?
- I think granular is a good thing, but to an extent. You do not want things to scattered around but also not have everything to much in one place. 

2. Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched
- If it was your intention, than a pro.

3. Name a strategy for preventing the above
- set a reducer to only fire one thing at a given event. 


### Vocabulary Terms: 

- Store:  is basically just a plain JavaScript object that allows components to share state. In a way, we can think of a store as a database. On the most fundamental level, both constructs allow us to store data in some form or another.[Source](https://learn.co/lessons/react-stores#:~:text=A%20store%20is%20basically%20just,in%20some%20form%20or%20another.)

- Combined Reducers: The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore . The resulting reducer calls every child reducer, and gathers their results into a single state object. [Source](https://redux.js.org/api/combinereducers#:~:text=The%20combineReducers%20helper%20function%20turns,into%20a%20single%20state%20object.)
