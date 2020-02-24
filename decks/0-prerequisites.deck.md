---
title: Prerequisites
---

# Prerequisites for the DevOps course

For the DevOps course it is required to be familiar with command line interface (CLI) usage and to have basic programming skills.

1. Using command line interface (CLI)

**References:**

  - For Windows users it is recommended to use [Git Bash](https://gitforwindows.org/) instead of normal CMD to have commands like in LINUX and UNIX environments.
  - Learn the most common commands - http://web.cs.ucla.edu/~miryung/teaching/EE461L-Spring2012/labs/posix.html

2. Basic programming skills

Javascript (with Node.js) was chosen as a programming language to built a basic application which will be used for the future DevOps classes. For these classes, we need to create a simple http-server exposing [REST API](https://en.wikipedia.org/wiki/Representational_state_transfer) covered by unit (functional, integration, etc.) tests.

Students might choose another programming language (C++, Java, Python, Ruby ...) to build their own simple http-server instead of using Node.js. In this case, the functionality of the app requires to have:

- http-server exposing a home page
- REST API (ex: create user, get user)
- using storage (file system or any database)
- full tests coverage using any test framework (JUnit for Java, Mocha for Node.js, etc.)
- using any package manager (Maven for Java, NPM for Node.js, etc.)

**References for Node.js:**

You can google tons of materials and tutorials (video and text) for learning Node.js. Many of them are starting from creating a basic http-server using [Express framework](https://expressjs.com/) or the internal Node.js [http module](https://nodejs.org/api/http.html#http_http).

Here are some references:

- Adaltas' course of Node.js for the ECE students - https://github.com/adaltas/ece-nodejs (structured differently, check the branches)
- Node.js Tutorial on w3schools - https://www.w3schools.com/nodejs/
- One more tutorial - https://www.guru99.com/node-js-tutorial.html
- Official Node.js documentation - https://nodejs.org/en/docs/
- About REST API - https://www.smashingmagazine.com/2018/01/understanding-using-rest-api/
- A bit info about Test Driven Development (TDD) - https://www.guru99.com/test-driven-development.html, https://en.wikipedia.org/wiki/Test-driven_development
