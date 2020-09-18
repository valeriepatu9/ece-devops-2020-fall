# Labs

Continuous testing

## Objectives

1. Use prepared User API application and run tests
2. Using test driven development (TDD) create GET user method

## Before starting

1. Install Redis dababase

- Windows: https://redislabs.com/ebook/appendix-a/a-3-installing-on-windows/a-3-2-installing-redis-on-window/
- MacOS: `brew install redis` or https://redis.io/topics/quickstart
- Linux: https://redis.io/topics/quickstart

After installation start Redis server:

```bash
redis-server
```

Test if Redis server is running (run in a new terminal window)
```bash
redis-cli ping
# Should answer with "PONG"
```

## 1. Use prepared User API application and run tests

Go to `asssets/userapi` folder and explore the project:

```
cd modules/4-continuous-testing/assets/userapi
```

Install application:

```
npm install
```

Run tests:

```
npm test
```

Start application:

```
npm start
```

## 2. Using test driven development (TDD) create GET user method

Create a REST API GET `user` method that retrieves user information form database

1. Create unit test for `get` user controller method
2. Create `get` user controller method
3. Create API test for a GET user route
4. Create GET user route

## Bonus tasks

1. Integrate Swagger UI using for example this package - https://www.npmjs.com/package/express-swagger-generator
