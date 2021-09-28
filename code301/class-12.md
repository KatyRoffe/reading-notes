# CRUD

## [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

- In your own words, describe what each group of status code represents:
  - 100’s = information codes. parts of the request is received, the remainder is to follow.
  - 200’s = success codes. request was accepted, doesnt mean it's successful
  - 300’s = redirection codes. the resources aren't available at that location.
  - 400’s = client error. timeouts, wrong URIs, missing authentication.
  - 500’s = server error. overwhelmed or unreachable servers.

- What is a status code 202?
  - accepted. valid request still to finish processing.

- What is a status code 308?
  - permenant redirect. needs a different URL to access the info.

- What code would you use if an update didn’t return data to a client?
  - 204 No Content

- What code would you use if a resource used to exist but no longer does?
  - 410 Gone

- What is the ‘Forbidden’ status code?
  - 403, clients has no permissions to access resource

## [Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/watch?v=fgTGADljAeg&ab_channel=WebDevSimplified)

- Why do we need to pull our MongoDB database string out of our server and put it into our .env?
  - It will allow us to connect to our database without the route being visible to outside sources

- What is middleware?
  - software that lies between the operating system and the apps running it

- What does app.use(express.json()) do?
  - recognizes an incoming request object as a JSON object

- What does the /:id mean in a route?
  - it is a parameter that we can request (req.params.id)

- What is the difference beween PUT and PATCH?
  - PUT modifies resources where the data updates the whole resource
  - PATCH modifies resouces where data updates only a portion of the resource

- How do you make a default value in a schema?
  - create a new document without a path set. this will mean the path is undefined, and will apply a default value

- What does a 500 error status code mean?
  - Internal Server Error. Unexpected conditions prevent request fulfillment

- What is the difference between a status 200 and a status 201?
  - 200 OK: default request has succeeded
  - 201 CREATED: request has succeeded and a resource has been created as a result

## Things I want to know more about

