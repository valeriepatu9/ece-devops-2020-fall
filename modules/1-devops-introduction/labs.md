# Labs

Introduction to DevOps

## Objectives

1. Start a project
2. Create a changelog file
3. Initialize a NodeJS package
4. Create a NodeJS script
5. Create a web application using ExpressJS package
6. Describe the project in a `README.md` file

## Before starting

1. Install an IDE or a text editor (ex: https://code.visualstudio.com/ or https://atom.io/)
2. Install Git, use for the installation:
  - Windows: https://gitforwindows.org/
  - Linux: https://git-scm.com/download/linux
  - MacOS: https://git-scm.com/download/mac   
  (Only for Windows users) Install Git Bash and use it as a command line terminal
3. Install NodeJS: https://nodejs.org/

## 1. Start a project

**Note!** Don't put spaces (` `) ether in folder names ether in file names. Otherwise, you will have to use escaping characters when navigating to them. Use "kebab-case" naming convention by separating words with dashes (`-`).

1. Using CLI commands navigate in your terminal to the directory where you will store your project folder.

Example:

```bash 
cd ~/path/to/your-root-project-directory
```

2. Choose a name for your project and create a directory

```bash
mkdir ece-devops
```

3. Initialize a Git repository

```bash
git init
```

## 2. Create a changelog file

`CHANGELOG.md` is a file that describes the evolution of the project. All notable changes will be documented in this file. 

1. Create the `CHANGELOG.md` file with the starting content

```md
# Changelog

## Unreleased

### Added

- Initialize a Git repository
- Create the project folder
```

2. Constantly update this file when working on the project. 

[Read more](https://keepachangelog.com/en/1.0.0/)

## 3. Initialize a NodeJS package

1. Initialize a NodeJS package running this command:

```bash
npm init -y
```

This will create an initial `package.json` file with the package description. 

2. Modify content in the `package.json` file respecting the JSON format:
  - change `author` name
  - change `description` of the package

3. Run the NPM script:

```bash
npm run test
# or
npm test
```

It will run the bash script `echo \"Error: no test specified\" && exit 1` defined in the `package.json` file, what outputs the string `Error: no test specified` to stdout.

## 4. Create a NodeJS script

1. Create a file `index.js` with the following content:

```js
str = "Hello NodeJS!"
console.log(str)
```

2. Run the NodeJS script in the terminal:

```bash
node index.js
```

It will print the message `Hello NodeJS!`.

3. Define this command as a NPM script. Modify in the `package.json` file like this:

```json
...
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "node index.js"
  },
...
```

4. Run the NPM scrip with the command:

```bash
npm run start
# or
npm start
```

It will do the same like in the step 2.

## 5. Create a web application using ExpressJS package

1. Install the [ExpressJS](https://www.npmjs.com/package/express) package:

```bash
npm install express
```

It will install the package files and its dependencies sourced on GitHub to you project directory inside `node_modules` folder.

2. Modify the `index.js` file with the following content:

```js
const express = require('express')

const app = express()
const port = 3000

app.get('/', (req, res) => {
  res.send('Hello World!')
})

module.exports = app.listen(port, (err) => {
  if (err) throw err
  console.log("Server listening the port " + port)
})
```

3. Run the NPM `start` script.

## 6. Describe the project in a `README.md` file

Create a `README.md` file and describe the project with a minimal information such as:
  - Short description
  - List of Functionalities 
  - Installation instructions
  - Usage instructions
  - Author information
