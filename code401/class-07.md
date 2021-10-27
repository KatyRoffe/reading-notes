# Bearer Authorization

## Steps
Correct Order?
Register your application to get a client_id and client_secret
Ask the client if they want to sign in via a third party
Make a request to a third-party API endpoint
Receive access token
Receive authorization code
Make a request to the access token endpoint
Redirect to a third party authentication endpoint

## 1. What can you do with an authorization code?

* they are used for entry or transactions where the user has restriction on what is accessible

## 2. What can you do with an access token?

* allows access to information from APIs

## What’s a benefit of using OAuth instead of your own basic authentication?

* it is considered more secure due to the OAuth tokens expiring and requiring reauthentication

## Vocab

* **Client ID:** a unique public identifier of a client application
* **Client Secret:** a "secret" known only to  an application and the authorization server
* **Authentication Endpoint:** security designed to ensure only authorized devices can connect to a given network/server/site
* **Access Token Endpoint:** where apps make a request to get an access token for the user
* **API Endpoint:** the point where an API and software connect
* **Authorization Code:**a password that authorizes a user to entera security-protected space
* **Access Token:** allows application to access APIs (in token-based auth)

## Materials

* [JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)
* [Intro to JWT](https://jwt.io/introduction/)
* [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)
* [npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)
