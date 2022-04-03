# Code 301 Reading 15 Authentication

## [What is OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

What is OAuth?

* Open protocol that can be used to give different webpages a standardized method of authorization.

Give an example of what using OAuth would look like.

* I make a website selling jean-shorts called 'mikey's jorts' and you can click 'login with google' button whereby Oauth will redirect to that sites authentication that user will login to and then authentication site passes user back to my jorts 'members-only' page

How does OAuth work? What are the steps that it takes to authenticate the user?

* Allows user to have authorization by taking their info from one site and working with another website to verify.

What is OpenID?

* A security technology specializing in authentication rather than authorization as above.

---
---

## [Authorization and Authentication flows](https://auth0.com/docs/flows)

What is the difference between authorization and authentication?

* authorization: 'who are you?'

* authentication:  'do you have access to do this?'

What is Authorization Code Flow?

* That is when a web app or something else exchanges an authorization code for a token.

What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

* When public clients request access tokens, some additional security concerns are posed that are not mitigated by code flow process alone.

What is Implicit Flow with Form Post?

* This is a flow used when the client side requesting cannot securely store client secrets.

What is Client Credentials Flow?

* A system running machine-to-machine on the back-end with DAEMONS to authenticate the ___APP___ rather than a ___USER___

What is Device Authorization Flow?

* Having user authorization process also going through a link or device to authorize the user

What is Resource Owner Password Flow?

* This is a flow having users input passwords on a interactive form, not recommended in most contexts.

---
---

<!-- review and skim: [Auth0 for single page apps](https://auth0.com/docs/libraries/auth0-react) -->

<===== [BACK!](README.md)
