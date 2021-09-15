# Topics

## [React Docs: Lists and Keys](https://reactjs.org/docs/lists-and-keys.html)

1. What does .map() return?

- takes an array of numrs and doubles their values

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

- loop through the numbers usuing map(),
- return a `<li>` element
- assign the array of elements to `listItems`
- include the `listItems` array inside a `<ul>`
- render to the DOM

3. Each list item needs a unique ____.

- key

4. What is the purpose of a key?

- the help React identify items that have been changed/removed/added
- they are stable identities for elements
- 

## [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

1. What is the spread operator?

- an ellipsis " ... "

2. List 4 things that the spread operator can do.

- copying an array
- adding items to a list
- adding to a state in React
- combining objects

3. Give an example of using the spread operator to combine two arrays.

> const cats = ['calico', 'tuxedo', 'siamese']<br>
> const moreCats = ['tortoise', 'tabby', 'ragdoll']<br>
> const allTheCats = [...cats,...moreCats]

4. Give an example of using the spread operator to add a new item to an array.

> const someTitans = ['attack', 'armored', 'colossal']<br>
> const moreTitans = ['beast', 'jaw', ...someTitans]

5. Give an example of using the spread operator to combine two objects into one.

> const dish = {temp: 'hot'}
> const drink = {flavor: 'sour'}
> const meal = {...dish, ...drink}

## [How to Pass Functions between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

1. In the video, what is the first step that the developer does to pass functions between components?

- created the function in the parent component so it could be passed later into the child component

2. In your own words, what does the increment function do?

- passes in an object, looks for a match, and updates the count of it by 1

3. How can you pass a method from a parent component into a child component?

- pass methods by using props, similar to variables

4. How does the child component invoke a method that was passed to it from a parent component?

- child components can access methods by using 'this.prop.propNameFromParent'

## Additional Resources
* [React Tutorial: delcare a winner](https://reactjs.org/tutorial/tutorial.html)
* [React Docs: lifting state up](https://reactjs.org/docs/lifting-state-up.html)

## Things I want to know more about
