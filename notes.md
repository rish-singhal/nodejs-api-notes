# API Design and NodeJS

## Table of Contents

- [API Design and NodeJS](#api-design-and-nodejs)
  - [Table of Contents](#table-of-contents)
    - [What is an API?](#what-is-an-api)
    - [Terminologies](#terminologies)
    - [Where does NodeJS comes in?](#where-does-nodejs-comes-in)
    - [MongoDB](#mongodb)
    - [Middleware](#middleware)
    - [Auth Basics/ JWT](#auth-basics-jwt)

### What is an API?

API is an interface that allows you to access data from a server or interact with some abstracted system.

### Terminologies

**CRUD:** Create, Read, Update, Delete
**REST**: Representational State Transfer; a desing pattern for APIs

Route paths, HTTP verbs, and Database resources are the three main components of an API.

### Where does NodeJS comes in?

- **Single Threaded:** Not good for CPU intensive tasks
- **Concurrent**
- **Asynchronous**
- **Even Driven**

Have [NPM](https://www.npmjs.com) (Node Package Manager) which have a good community contributing many packages to the NodeJs ecosystem. For example ExpressJS.

### MongoDB

Non-relational document store, storing JSON like a blob.

~ Have tons of hosting solutions. For example Atlas

**ORM/ ODM:** Object Relational Mapper (ORM) converting data types in and out.

MongoDB is a Schemaless document store, but one can also use schemas to enforce data types.

***Q:*** What is hooks for a Database?
***A:*** Hooks are functions that are called before and after a database operation.

### Middleware

Some functions which are executed on the request object before the controller handles it. 
~ Middlewares can also response to the request like controller although it is not the intention.

ExpressJs allows to use different mioddlewares as modules to process the request.

### Auth Basics/ JWT

**Authentication** is controlling if the incoming request can pass through.

**Authorization** is controlling if the authenticated request can access certain resources (checking if they have permissions.)

**JWT** are tokens passed with each request to check if the user is authenticated. JWT is stateless in the sense that it does not remember the state of the user which have certain `x` token.

JWT is one of the **bearer** (which basically denotes a client node which may be unauthorized) authentication methods.
