# Code 301 Reading 8: APIs

## [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

What does REST stand for?

* Representational State Transfer

REST APIs are designed around a resource that can be accessed by the client, like an object.

What is an identifer of a resource? Give an example.

* identifier is a unique URI

  > ex: https://mics-garden-zoo.com/orders/ultra-sectret/1

What are the most common HTTP verbs?

* GET, POST, PUT, PATCH, DELETE

What should the URIs be based on?

* They should be based on the resource

Give an example of a good URI.

> https://mics-garden-zoo.com/orders // Good

Give an example of a bad URI.

> https://mics-garden-zoo.com/create-order // Avoid

What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

* Client applications sending many API requests in order to obtain the data it wants.

What status code does a successful GET request return?

> HTTP status code 200 (OK)

What status code does an unsuccessful GET request return?

> HTTP status code 404 (Not Found)

What status code does a successful POST request return?

> HTTP status code 201 (Created)

What status code does a successful DELETE request return?

> HTTP status code 204 (No Content)

<===== [BACK!](README.md)
