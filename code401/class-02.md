# Express

1. What’s the difference between [PUT and PATCH](https://www.geeksforgeeks.org/difference-between-put-and-patch-request/)?

    * `PUT` updates an entire resource
    * `PATCH` updates a portion of a resource

2. Provide links to 3 services or tools that allow you to “mock” an API for development like json-server.

    * [Swagger](https://swagger.io/solutions/mocking-and-virtualization/)
    * [Mock Service Worker](https://mswjs.io/)
    * [Postman](https://www.postman.com/)

3. Compare and contrast Swagger and APIDoc.js

    * [Swagger](https://swagger.io/): Open sourced, can be used on the web and on a local maching
    * [APIdoc.js](https://apidocjs.com/): Can only be used on a local machine

4. Which HTTP [status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status) should be sent with each type of (un)successful API call?

    * Client side: 400s codes
    * Server side: 500s codes

5. Compare and contrast [SOAP and ReST](https://www.guru99.com/comparison-between-web-services.html)

    * SOAP: Simple Object Access Protocol
        * a protocol
        * uses service interfaces to expose functionality
        * needs more bandwidth
        * only works with XML formats
        * cannot use REST

    * REST: Representational State Transfer
        * an architectural pattern
        * uses Uniform Service locators to access the components
        * needs little bandwidth
        * works with plaintext, XML, HTML, and JSON
        * can use SOAP

## Document the following Vocabulary Terms

* Web Server: It stores and delivers content for a site.
* Express: A node.js application framework. It provides features for applications and featuresests to access them.
* Routing: A URL ouptut that direct the front-end where to meet the back-end
* WRRC: Web Request Response Cycle. It describes the relationship between the client side and a server when it comes to requests and responses.

## Additional Materials
* [Intro to Node](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)
* [What is NPM](https://docs.npmjs.com/getting-started/what-is-npm)
* [What is TDD](https://www.agilealliance.org/glossary/tdd/)
* [CI/CD](https://www.youtube.com/watch?v=xSv_m3KhUO8)
