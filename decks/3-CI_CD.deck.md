---
title: Continuous Integration and Delivery (CI/CD)
---

# DevOps course overview

- DevOps culture
- Source Control Management (SCM) - Git
- **Continuous Testing**
- **Continuous Integration & Continuous Delivery (CI/CD) - Travis CI**
- Containers - Docker
- Containers orchestration - Kubernetes
- Infrastructure as code (IaC) - Ansible
- Cloud native architecture

A project at the end of the course (based on the class works and the homeworks).

gatsby-slide

# Continuous Testing

## Types of tests

### Unit tests

- Lowest level of testing
- Test an individual unit (or function) of a software
- Tests are run in very controlled environment

### Functional tests

- Higher level function testing
- Test outside dependencies
- Example: Database connection, API

### Integration tests

- Assemble project modules
- Test how project modules react together

### End-To-End tests

- Test the application in a real environment
- Use production-like database
- UI testing
- Acceptance testing

gatsby-slide

# Continuous Testing

## Test driven development (TDD)

- Write test before writing the associated function
- Make sure all the tests are successful

## Test Automation

- Run tests on a server with specific configuration specified in your tests
- Run the tests on different version of the code
  - Condition for PullRequest merge
  - On each commit
- Run on your own server

gatsby-slide

# Continuous Integration and Delivery (CI/CD)

## Continuous Integration (CI)

This is a software development practice in which members of a team integrate their work frequently, at least daily, leading to multiple integrations per day.

## Continuous Delivery (CD)

This is a software development discipline where software is built in a manner that allows for deploying to customers at any time.

##  Continuous Deployment

This extends Continuous Delivery by automating the deployment process so that code is automatically deployed to production after it passes automated testing.

gatsby-slide

# What is the CI/CD Pipeline?

**CI/CD pipeline** - an automated sequence of events that is initiated after you update the code.

These events take care of the work that you would otherwise need to perform manually:
- previewing your in-development site
- testing your new code
- deploying it to your production server

gatsby-slide

# CI/CD with Travis CI and deployment platforms

[Travis CI Tutorial](https://docs.travis-ci.com/user/tutorial/)

## CD using Heroku

[Heroku Deployment](https://docs.travis-ci.com/user/deployment/heroku/)

[Automatically deploy with Travis CI and Heroku (article)](https://medium.com/@felipeluizsoares/automatically-deploy-with-travis-ci-and-heroku-ddba1361647f)

## CD using Netlify

[Netlify Drop](https://app.netlify.com/drop)

[Netlify Drop Deployment](https://docs.travis-ci.com/user/deployment-v2/providers/netlify/)

gatsby-slide

# The CI/CD Pipeline Sequence

The flow of events:

1. You create a new branch in your local Git repository and make code changes to your Gatsby project.

2. You push your branch to your GitHub repository and create a pull request.

3. Netlify automatically creates a preview of the site with a unique URL that can be shared.

4. Travis CI automatically builds the site in an isolated container and runs any declared tests.

5. When all tests pass, you merge the PR into the repository’s master branch, which automatically triggers a deployment to your production.

gatsby-slide

# Your work

1. ...
