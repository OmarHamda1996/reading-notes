## ES6 Classes

Classes are a blueprint for creating objects. A class declaration cannot be hoisted. It means you need to define a class before using it in your code. A constructor is a special function inside a class that creates and sets up objects based on the class. It's like a factory that builds specific objects with their initial properties. The contextual "this" refers to the current object being worked on. It allows the object to access its own properties and methods. It's like referring to yourself while doing something.

## Using Express Routing

Routing in Express refers to how an application handles client requests at specific endpoints (URLs). It determines which function or middleware should be called based on the requested URL and HTTP method. A route path is the URL endpoint to which requests are made. It can be a string or a pattern that matches the requested URL. A route method corresponds to an HTTP method (e.g., GET, POST) and defines the action to be taken when a request matches both the method and the path. Adding `next` as a parameter to a route handler allows passing control to the next function or middleware in the chain. If `next` is passed to your middleware, remember to call `next()` to continue to the next function. Otherwise, the request may get stuck and not proceed further.

## Express Routing

An Express Router is a feature in Express JS 4.0 that helps in creating modular routes for web applications. To initialize `express.Router()` in an Express server, we simply call the function and assign it to a variable. Route middleware is used to perform actions before handling a request, such as authentication, logging, validation, or error handling. It allows us to add custom logic to specific routes or all routes.

## Things I want to know more about

- Understand the concept and usage of ES6 classes for object creation.
- Learn how to define and use constructors in classes to set up objects with initial properties.
- Gain a clear understanding of the "this" keyword and its role in accessing object properties and methods.
- Master the implementation of Express routing to handle client requests at specific endpoints.
