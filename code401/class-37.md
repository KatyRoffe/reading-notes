# Redux - Combined Reducers

1. Why choose Redux instead of the Context API for global state?

- helps manage global state and make it easier to track changes

2. What is the purpose of a reducer?

- it manages the changes of state

3. What does an action contain?

- it is an object with an action type and action payload

4. Why do we need to copy the state in a reducer?

- reducers do not modify state. they make updates to modified copies of the state. this keeps things "pure."


## Vocab

- **immutable state:* the value can't be changed upon its creation
- **time travel in redux:** going back and forth between states in the app
- **action creator:** function that creats an action
- **reducer:** function that takes a state, applies an action, and returns a new state
- **dispatch:** function that triggers a state change

## Materials

- [Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)
- [Redux Docs: Using Combined Reducers](https://redux.js.org/recipes/structuring-reducers/using-combinereducers/)
- [Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)
