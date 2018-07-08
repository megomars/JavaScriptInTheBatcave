# Javascript in the Batcave

## What are all the new features in ES6 that you really have to know?
1. Loops, Conditionals, Functions, constructors and Objects recap
2. Closures, prototypes and promises
3. Template literals
4. Destructing objects
5. Destructing arrays
6. Object literals
7. For of Loop
8. Spread Operator
9. Rest Operator
10. Arrow Functions 
11. Default params
12. includes()
13. Let and Const
14. Import and Export
15. padStart() and padEnd()
16. Classes
17. Trailing Commas
18. Async and Await
19. Sets
20. Web APIs

### Some random code snippets

Running strict mode within an iffy.
```Javascript
(function(){
'use strict'
})();

```

Defining functions

```Javascript
//define the function (function declaration)
function fun(a,b){
    return a+b;
}
//define the function (anonymous function expression)
var fun = function(){

};
//define the function (named function expression)
var fun = function fun(){

};
//a and b are called parameters

//invoke the function
fun(2,3)
//2 and 3 are called arguments

```