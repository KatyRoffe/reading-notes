# Readings

## [React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

1. What is the single responsibility principle and how does it apply to components?

- components should ideally only do one thing. if it does more than one thing - break it down into  subcomponents.

2. What does it mean to build a ‘static’ version of your application?
Once you have a static application, what do you need to add?

- a static version is a data model that renders the UI but accepts no interactivity
- a static version should use components that reuse other components and pass data using props. **don't use state** 
- once the static app is complete, then you can make it interactive by using state
- figure out the minimal representation of state needed

3. What are the three questions you can ask to determine if something is state?

- is it passed in from parent via props? (likely not state)
- does it remain unchanged over time? (likely not state)
- can you compute it based on any ther state or props in a componenet? (isn't state)

4. How can you identify where state needs to live?

- identify all the components that render something with state
- find a common owner component
- either the common owner or another higher level component should own the state
- if there are no components where it makes sense to own this state, create a new component and add it in the hierarchy somewhere above the common owner

## [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

1. What is a “higher-order function”?

- functions that operate on other functions
- this can be either taking them in as arguements or returning them

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

- line two of the greaterThan function compares whether or not "m" is greater than the argument (n)

3. Explain how either map or reduce operates, with regards to higher-order functions.

- map transforms an array: applies a function to all elements -> builds a new array from the results
  - new array will be the same length of the previous array, but content will have been *mapped* to a new form by the function

## Things I want to know more about

- Practicing the methods of building a code based on today's React reading
- find materials that explain 'reduce' in a way that is easier for my brain to process