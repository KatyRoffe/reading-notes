# Context API

1. Describe use cases useState() vs useReducer()

    - useReducer is beter for complex state logic involving multiple values / also good for when a state relies on a previous one

2. Why do custom hooks need the use prefix?

    - helps to automatically check for violations of rules, because we couldn’t tell if a certain function contains calls to hooks inside of it
    - distinguishes between helper functions and custom hooks 

3. What do custom hooks usually do?
    
    - allow us to have cleaner functional components and prevent code duplication by bringing common use cases to reusable hook
 
4. Using any list of custom hooks, research and name one that you think will be useful in your applications

    - [react-collapsed](https://www.npmjs.com/package/react-collapsed) might be useful for keeping an apps visual look clean

5. Describe how a hook that fetches API data might work

## Vocab

- **reducer:** a function to change state

## Materials

- [context api](https://reactjs.org/docs/context.html)
- [hooks and context example](https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b)
- [react context links](https://github.com/diegohaz/awesome-react-context)