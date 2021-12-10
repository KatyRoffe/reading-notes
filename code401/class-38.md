# Asynchronous Actions

1. How granular should your reducers be?

- There should be separate reducers for each portion of data. 

2. Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched

- I'd call it a con. You might update the state of componenets you didn't intend to. 

4. Name a strategy for preventing the above.

- Use specific names for each reducer to represent what it should do. 

## Vocab

- **store:** a collection of reducers
- **combined reducers:** an object containing the properties of many reducers

## Materials

- [async actions](https://redux.js.org/advanced/asyncactions)
- [thunk middleware](https://github.com/reduxjs/redux-thunk)
- [redux thunk](https://alligator.io/redux/redux-thunk/)
