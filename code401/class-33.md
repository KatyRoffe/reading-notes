# Login & Auth

1. Why is the Context API useful?

- you can pass global data to children components without having to manually pass down props.

2. Can a component outside of a provider get its context?

- yes through the useContext() hook

3. What are some common use cases for using the Context API?

- global layouts/themes, auth

4. Describe “Context Hell”

- nested context providers all the way down

## Vocab

- **global state:** data that all components share
- **global context:** a way to share context between components without passing props
- **provider:** a component that provides info to other components
- **consumer:** a component that receives info from the provider

## Materials

- [what is role based access control?]()
- [react-cookies component]()
- [react-cookie library]()
