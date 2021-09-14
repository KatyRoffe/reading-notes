# [React Lifestyle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

## 1. Based off the diagram, what happens first, the `render` or the `componentDidMount`?

- Render

## 2. What is the very first thing to happen in the lifecycle of React?

- The `constructor` for a React component is called

## 3. Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`

1. constructor
2. render
3. react updates
4. componentDidMount
5. component WillUnmount

## 4. What does `componentDidMount` do?

- it is a method invoked after a component is mounted
- anything requiring a network request to load should go here
- DOM manipulations should also go here. 
- it's a good place to set up subscription 

# [Props vs. State](https://www.youtube.com/watch?v=IYvD9oBCuJI&ab_channel=WebDevSimplified)

## What types of things can you pass in the props?

- information that you want to display without the need to hard code it, that will be passed down from the parent
  - like titles, descriptions, and images

## What is the big difference between props and state?

- props are passed *into* a componenet (props can't be changed in a component (it is likely a state elsewhere in the app being passed down as props)
- state is handled inside a componenet while props are handled outside the componenet

## When do we re-render our application?

- when the state is changed due to an user event, the application will re-render

## What are some examples of things that we could store in state?

- things that need updating and re-rendering based on something the user has done
  - like counter applications or forms

# Things I want to know more about

- finding more examples of when to best use prop and state


### Additional Resources

[React Bootstrap](https://react-bootstrap.github.io/)<br>
[Netlify](https://www.netlify.com/)<br>
<br>
[React: State & Lifestyle](https://reactjs.org/docs/state-and-lifecycle.html)
[React: Handling Events](https://reactjs.org/docs/handling-events.html)
[React: Tutorial thru dev tools](https://reactjs.org/tutorial/tutorial.html)