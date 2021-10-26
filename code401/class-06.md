# Authentication

## Readings & Research

### Explain what a “Singleton” is (in Computer Science terms)

* a design pattern that restricts the instantiation of a class to a single instance
* [source](https://betterprogramming.pub/what-is-a-singleton-2dc38ca08e92)

### Explain how the Singleton pattern can be used with Node modules, specifically with classes

* a constructor is called only when the object is requested the first time through the specified method
* the object is then saved in the sington class as a private field value
* the next time the specified method is called, the class returns the object that was created the first time
* no new objects are created
* [source](https://opensource.com/article/19/7/understanding-software-design-patterns)

### If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?

## Vocab

* **Router Middleware:** acts the same as appliction middleware, only its bound to an instance of express.Router()
* **Dynamic Module Loading:** a mechanism that allows you to load modules where they are needed at runtime instead of up front and all at once
* **Singleton Pattern:** a design pattern that restricts the instantiation of a class to a single instance
* **CRUD -> REST Method Matches:**
  * Create --> POST
  * Read --> GET
  * Update --> PUT or PATCH
  * Delete --> DELETE
* **Mock Testing:** creating a fake version of external/internal services as as a temp stand in for a real one to help with runnings tests

## Materials

* [Securing Passwords]https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html()
* [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)
* [OWASP auth cheatsheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet)
* [bcrypt docs](https://www.npmjs.com/package/bcrypt)
