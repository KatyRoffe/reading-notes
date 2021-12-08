# Application State with Redux

1. What are the advantages of storing tokens in “Cookies” vs “Local Storage”

- cookies are more secure due to being designed for server side reading

2. Explain 3rd party cookies.

- cookies planted by a site other than what the user is browsing. these are designed to track users and provide relevant data (ads) based on browsing history

3. How do pixel tags work?

- aka a tracking pixel, they load when a user accesses a website/email. the code used to implant a pixel contains an external link to the pixel server and when the code is processed by the client, the broswer follows the link. it is then registered in the server's log.
[source](https://en.ryte.com/wiki/Tracking_Pixel)

## Vocab

- **cookies:** pieces of data to help track and store info about a user
- **authorization:** granting a user access to a resource
- **access control:** rules designed to establish who can access what
- **conditional rendering:** the act of loading components based on specific sets of circumstances

## Materials

- [Dan Abramov Redux Tutorials](https://egghead.io/courses/getting-started-with-redux)
- [worlds easiest guide to redux](https://medium.freecodecamp.org/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6)
- [testing reducers](https://medium.com/@netxm/testing-redux-reducers-with-jest-6653abbfe3e1)
- [Redux Docs](https://redux.js.org/)
