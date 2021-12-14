# Redux - Additional Topics

1. What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?

- fire off an async action in the lifecycle method of a higher order component that wraps your app

2. When using a thunk/async action that dispatches the actual action, which do you export from your reducer?

- the function

## Vocab

- **middleware:** functions that run between two operations
- **thunk:** middleware that allows you to write actions creators that return functions instead of objects

## Materials

- [Redux Toolkit (RTK)](https://redux-toolkit.js.org/)
- [Tutorial](https://redux-toolkit.js.org/tutorials/intermediate-tutorial)
**alternative state managers**\
- [MobX](https://mobx.js.org/getting-started.html)
- [HookState](https://hookstate.js.org/)
