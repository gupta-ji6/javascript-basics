# Module 1 - The Missing Introduction to JavaScript

## Chapter 2: Modern JavaScript

### Package Management

* A typical JS project has more than one dependency.
* Dependencies are the code project libraries like date-pickers, carousels, etc that you would like to include in your project to make programming lives easier. 
* A package manager simply is used to manage these packages and their versions in our project.

### Local HTTP Server

* A development server which serves our project locally on our computer.
* Modern servers have various functionalities such as Live Reload which makes it productive.

### Transform ES6 and beyond to ES5

* As stated in previous chapter, Babel is used to transform the code written following ES6 standards to that of ES5.
* This operation is done every single time we save our code.

### Module Management (Bundling our dependencies)

* Webpack is the tool which is used to perform module management in JavaScript.
* We just need to set it up once and it does the rest work by itself every time.
* Webpack simply bundles all the module code in a single file so that we can focus on building our app, not on managing these modules.
* It's easier to scale our application with Webpack.
* It also performs advanced operations like Lazy Loading and Code Splitting without doing work on our end.

### Linting our code

* Linters analyse our code on the fly to pick up any potential errors.

### Tools

| Task                  | Tools
| --------------        | -------------
|Package Management     | [npm](https://www.npmjs.com/)
| Local HTTP Server     | [NodeJS](https://nodejs.org/)
|Transform ES6 to ES5   | [Babel](https://babeljs.io/)
| Module Management     | [Webpack](https://webpack.js.org/)
| Linting Code          | [ESLint](https://eslint.org/)

### How these tools work together?

1. NodeJS helps us to setup our local development environment.
2. After installation, NodeJS is now accessible through our command line.
3. npm ships with NodeJS by default.
4. `package.json` is the file which contains a list of all dependencies of our project. We can create this list by running `npm init` command in our project repository.
5. Any other libraries can be installed from npm with following command
`npm install name-of-dependency --options`.
6. npm downloads the dependencies and store them in the `node_modules` folder.
