# APIs

## [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

* What does REST stand for?
  - Representational State Transfer

* REST APIs are designed around a ____.
  - Resource (any kind of object, data, or service)

* What is an identifer of a resource? Give an example.
  - a unique URI. URIs identify a specific resource. URLs tell you how to access them. 
  - further reading [difference between uri & url](https://danielmiessler.com/study/difference-between-uri-url/)

* What are the most common HTTP verbs?
  - GET, POST, PUT, DELETE, PATCH

* What should the URIs be based on?
  - nouns (the resource) as opposed to verb (the operation of the resource)

* Give an example of a good URI.
  - `https://sitenamehere.com/orders`

* What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
  - large requests that expose more than necessary of the resources
  - avoid anything longer than: `https://sitenamehere.com/collection/items/collection/`

* What status code does a successful GET request return?
  - 200 (OK)

* What status code does an unsuccessful GET request return?
  - 404 (Not Found)

* What status code does a successful POST request return?
  - 201 (Created)

* What status code does a successful DELETE request return?
  - 204 (No Content)

## RegEx
- [RegExr](https://regexr.com/)
- [Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
- [101](https://regex101.com/)
- my name would be matched using `^Katy Roffe$`

## Things I want to know more about
- can't really wrap my head around real world applications of using RegEx, so looking forward to covering that