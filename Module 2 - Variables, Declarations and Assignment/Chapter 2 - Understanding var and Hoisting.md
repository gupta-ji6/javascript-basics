# Module 2 - Variables, Declarations and Assignment

## Chapter 2: Understanding var and Hoisting

### Variables

+ JavaScript variables are loosely-typed which means it does not require a data type to be declared. You can assign any type of literal values to a variable e.g. string, integer, float, boolean etc.
+ `var` keyword is used to create a variable in JavaScript (in ES5 to be specific).

### JavaScript Hoisting

+ Basically, when Javascript compiles all of your code, all variable declarations using var are hoisted/lifted to the top of their functional/local scope (if declared inside a function) or to the top of their global scope (if declared outside of a function) regardless of where the actual declaration has been made. This is what we mean by “hoisting”.
+ Functions declarations are also hoisted, but these go to the very top, so will sit above all of the variable declarations.
+ Before compilation:

```javascript
var a = 7;
console.log(a);
```

+ After compilation:

```javascript
var a; // variable declaration hoisted to the top
a = 7; //initialization
console.log(a);
```

For further reading about Hoisting in JavaScript, read this [article by Sunil Sandhu](https://medium.com/javascript-in-plain-english/https-medium-com-javascript-in-plain-english-what-is-hoisting-in-javascript-a63c1b2267a1).

