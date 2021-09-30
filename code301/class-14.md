# Authentication

## [What is OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

- What is OAuth?
  - authorization protocol. describe how unrelated servers can safely allow authenticated access to assets

- Give an example of what using OAuth would look like.
  - logging onto a website that allows you opportunities to log onto another website's services. 
  - so probably the way you can access github through connecting accounts from other coding resource sites

- How does OAuth work? What are the steps that it takes to authenticate the user?
  - website A connects to website B on behalf of user
  - website B generates one-time token and one-time secret
  - webiste A gives the token to the user's client software
  - client software gives token to the authorization provider
  - client is asked to authenticate and approve the authoriation transaction
  - user or software approves transaction type
  - user is given approved access token
  - user gives access token to website A
  - website A gives access token to website B
  - website B lets website A access site
  - user gets successfully completed transaction

- What is OpenID?
  - it is authentication: humans logging into machines
  - it differs from OAuth (authorization, machines logging into machines on behalf of humans)

## [Authorization and Authentication flows](https://auth0.com/docs/authorization/flows)

- What is the difference between authorization and authentication?
  - authentication: process verifies who a user is
  - authorization: process verifies what a user can access

- What is Authorization Code Flow?
  - exchanges authorization codes for tokens

- What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
  - intrdouces "secrets" that can be verified by the server

- What is Implicit Flow with Form Post?
  - less secure alternative of Authorization Code Flow

- What is Client Credentials Flow?
  - client ID & secret are passed along to get a token

- What is Device Authorization Flow?
  - devices are authorized through a provided link. this is for input-constrained devices

- What is Resource Owner Password Flow?
  - requests users provide credentials (username/password)

## Things I want to know more about
