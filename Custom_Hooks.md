# Custom Hooks

1. What does a component’s lifecycle refer to?
- It refers to the 3 phases in which we are mounting, updating and unmounting. 

2. Why do you sometimes need to “wrap” functions in useCallback when called from within useEffect
- useCallback() often is used in conjunction with useEffect() because it allows you to prevent the re-creation of a function. ... Therefore, if you have a function (A) inside of a function (B), the inner function (=A) will be recreated (i.e. a brand-new object is created) whenever the outer function (B) runs. [Source]()

3. Why are functional components preferred over class components?
- For one thing, it is a lot cleaner. We do not have to refer to the contextual (.this) all the time. Also class function also have to do more, in a way that it has to extend React.Component. 

4. What is wrong with the following code?
import React, {useState, useEffect} from 'react';

function MyComponent(props) {
  const [count, setCount] = useState(0);

  function changeCount(e) {
    setCount(e.target.value);
  }

  let renderedItems = []

  for (let i = 0; i < count; i++) {
    useEffect( () => {
      console.log('component mount/update');
    }, [count]);

    renderedItems.push(<div key={i}>Item</div>);
  }

  return (<div>
     <input type='number' value={count} onChange={changeCount}/>
      {renderedItems}
    </div>);
}


## Vocabulary Terms

- State Hook: Hooks are a new addition in React 16.8. They let you use state and other React features without writing a class. [Source](https://reactjs.org/docs/hooks-state.html#:~:text=Hooks%20are%20a%20new%20addition,features%20without%20writing%20a%20class.)

- Effect Hook: lets you create side effects like data fetching, setting up a subscription, and manually changing the DOM in React components are all examples of side effects. Whether or not you’re used to calling these operations “side effects” (or just “effects”), you’ve likely performed them in your components before.[Source](https://reactjs.org/docs/hooks-effect.html)

- Reducer Hook: useReducer is one of a handful of React hooks that shipped in React 16.7. 0. It accepts a reducer function with the application initial state, returns the current application state, then dispatches a function.
[Source](https://css-tricks.com/getting-to-know-the-usereducer-react-hook/#:~:text=useReducer%20is%20one%20of%20a,state%2C%20then%20dispatches%20a%20function.)