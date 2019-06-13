# Module 1 - The Missing Introduction to JavaScript

## Chapter 1: Introduction

* JavaScript is a _high-level interpreted_ programming langauge with **Types**, **Operators** and standard building **Objects** and **Methods**.

| Interpreted Langauge        | Compiled Langauge           
| -------------               |-------------
| Human readable              | Machine readable
| Translation as it's executed| Translation in build step
| Run-time errors             | Compile-time errors
| Eg. JavaScript              | Eg. TypeScript, C, Java

* JavaScript is a multi-paradigm langauge because of it's support for multiple programming styles like **Imperative, Procedural, Object-oriented** and **Functional**.

### History of JavaScript

Mocha (1995) -> LiveScript -> JavaScript -> ECMAScript (1997) -> ECMAScript 5 (2009) -> ES2015 (2015) -> ES6 & Beyond

### What is Babel?

* All the browsers didn't supported all the new features which were introduced in ES6 and beyond. So, Babel was developed.
* [Babel](https://babeljs.io/) is a toolchain that is mainly used to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript in current and older browsers or environments.

### JavaScript Engine

* Computers run JavaScript code in browsers via the JavaScript Engine.
* JS Engine lives in the browser and essentially executes our code.
* [v8](https://v8.dev/) is a JS Engine built by Google for Google Chrome which is Open Source.
* v8 uses Just-In-Time (JIT) compiler. For performance optimisation, v8 transform JS code to machine code instead of using interpretor.
* [NodeJS](https://nodejs.org/) took the v8 JavaScript Engine outside the browser which allowed us to run JavaScript on other platforms. Now, NodeJS made it possible to run JavaScript code not only on front-end, but also on back-end.

### Document Object Model (DOM)

* [DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction) is an API for HTML and XML documents which provides us structural represenation of the document which can be then interact by JavaScript.
* JavaScript is a seperate entity which can talk to the DOM via API's.
* However, in NodeJS there is no DOM because there is no browser. It's a server-side environment.