# Express REST API

## Name 3 real world use cases where you’d want to change the request with custom middleware

- add a time stamp to a request
- logging / display a message
- triggering an error handler

## True or false: The route handler is middleware?

- false

## In what ways can a middleware function end the process and send data to the browser?

- response.end()
- response.status('###').send('message')

## At what point in the request lifecycle can you “inject” middleware?

It can be injected between the HTTP method and the path is it being directed to.

## What can cause express to error with “Request headers sent twice, cannot start a second response”

- another function has tried to set the header or a status code
- a callback might have been called twice

### Vocab

- **Middleware**:  functions that have access t both the request and response abjects
- **Request Object**:  data representing an HTTP request comprised of a query string, paramerters, body,and HTTP headers
- **Response Object**:  the data received as a result of an HTTP request
- **Application Middleware**:  sends requests to the server by using `app.use()` or `app.get()`.
- **Routing Middleware**:  acts the same as appliction middleware, only its bound to an instance of express.Router().
- **Test Driven Development**:  Deciding what you want your application to do, formulating a failing test, and then writing code to make it work
- **Behavioral Testing**:  testing the external behavior of a program (black box testing)

### Materials

[Review ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
[Using Expess Routing](https://expressjs.com/en/guide/routing.html)
[Expess Routing](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4)
