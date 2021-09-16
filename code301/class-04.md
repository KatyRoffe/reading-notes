# Reading

## [React Docs - Forms](https://reactjs.org/docs/forms.html)

1. What is a ‘Controlled Component’?

- a component where React takes over the state of it 
- for example: in a form, rather than HTML controlling the  

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

- update the state with the responses as soon as they're entered
- the component should serve as a "single source of truth" 

3. How do we target what the user is entering if we have an event handler on an input field?

- event.target.value


# [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff?gi=f1264586c7a5)

1. Why would we use a ternary operator?

- they can make code shorter and easier to read / unforunately they can also make things harder to read in certain circumstances

2. Rewrite the following statement using a ternary statement:

> Original
>`  if(x===y){
> console.log(true);
>  } else {
> console.log(false);
>  }`

> Ternary
> x === y ? console.log(true) : console.log(false)

## Additional

- [React Bootstrap - Forms](https://react-bootstrap.github.io/components/forms/)
- [React Docs - conditional rendering](https://reactjs.org/docs/conditional-rendering.html)

## Things I want to know more about

