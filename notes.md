# API Design and NodeJS

## Table of Contents

- [API Design and NodeJS](#api-design-and-nodejs)
  - [Table of Contents](#table-of-contents)
    - [What is an API?](#what-is-an-api)
    - [Terminologies](#terminologies)
    - [Where does NodeJS comes in?](#where-does-nodejs-comes-in)
    - [MongoDB](#mongodb)
    - [Middleware](#middleware)

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

### Middleware

Some functions which are executed on the request object before the controller handles it.
