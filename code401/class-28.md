# Component Lifecycle

1. Why do we not need more .html pages in a multi-page React app?

- React is a single page app utilizing React Router to create routes to different "pages"

2. If we wanted a component to show up on every page, where would we put it and why?

- Inside the `<BrowserRouter />`, outside a `<Route />`
- Components within a `<Route />` are like pages, but anything outside `<BrowserRouter/>` are not routes within the app

3. What does routing do with the components that were rendered when a new route is requested

- they are unmounted

3. What does props.children contain?

- children of the component

4. How do useState() and this.setState() differ?

- useState() is used in a functional component
- this.setState() is used in a class component

## Vocab

- **State Hook:** lets you add state to functional components rather than converting them to a class
- **Mounting and Un-Mounting:** When a component is created and inserted into the DOM / When a component is removed from the DOM 

## Materials

-[effects hook](https://reactjs.org/docs/hooks-effect.html)