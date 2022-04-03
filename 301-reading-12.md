# Code 301 Reading 12 CRUD

## [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

### What each group of status code represents

* 100’s = Informational code coming back to inform user that request header at least is received and that will contain other applicable initial info

* 200’s = These are called success codes and they are sent back to client to inform successful body receipt

* 300’s = Address user is directing towards does not exist at that location so they will be redirected elsewhere

* 400’s = These are specifically referencing errors from the request sent from the client

* 500’s = Indicate the problem likely lies in the server

---

What is a status code 202?

* Tells client the request was ___accepted___

What is a status code 308?

* This tells client there's a new url and is thus giving a permanent redirect.

What code would you use if an update didn’t return data to a client?

* Update 204: No Content

What code would you use if a resource used to exist but no longer does?

* Update 410: Gone

What is the ‘Forbidden’ status code?

* 403: client doesn't have permission to access

---
---

## [Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

Why do we need to pull our MongoDB database string out of our server and put it into our .env?

* Because we do not want our sensitive information to be posted

What is middleware?

* Some software used between systems to ensure the sending and receiving end see compatible data

What does app.use(express.json()) do?

* Lets our server accept JSON as a body

What does the /:id mean in a route?

* Makes it an accessible parameter with `req.params.id`

What is the difference between PUT and PATCH?

* Put updates an object in it's entirety, while Patch updates PART of an object

How do you make a default value in a schema?

* Have the schema be an object with specific `key:value` pairs, set the key to `default: something` to give it a default value

What does a 500 error status code mean?

* An internal service error existing on the server/database

What is the difference between a status 200 and a status 201?

* 200 = OK 201 = CREATED

---
---

<===== [BACK!](README.md)
