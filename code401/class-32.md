# Context API - Behaviors

1. When you have multiple contexts, what component type should you use (class/function) and why?

I think it probably comes down to preference given there are pros and cons to both class and functional components. 

2. What are some good use cases for using the Context API for global state?

Context global state eliminates the need to pass props between components, so it's useful for implementing things across an entire application, such as a light/dark theme. 

3. How can you best test context?

Make the test unaware of its existence and avoid mocks.

## Vocab

- **context:** provides a way to pass data between components without passing props at every level 
- **useContext():** accepts a context object and returns the current context value for that context
- **static context:** eqivalent to useContext(MyContext) in a class, or <MyContext.Consumer>/ given the definition of static, I'd guess it can't be modified

## Materials

- [context api](https://reactjs.org/docs/context.html)
- [hooks and context example](https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b)
- [react context links](https://github.com/diegohaz/awesome-react-context)

