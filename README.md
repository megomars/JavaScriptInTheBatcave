# Javascript in the Batcave

A basic rundown of the Javascript language including ES6+

## Language Fundementals

### Variables
### Data types
### Operators
### Strict mode

Running strict mode within an iffe.
```Javascript
(function(){
'use strict'
})();

```

## Data structures

### Arrays
### Objects

### Sets
Sets are JavaScript objects that store unique values of any type. Set is one of the collection classes recently added to JavaScript.
```Javascript
let arr=[2,3,4,5,7];
let mySet= new Set(arr);
console.log(myset);
console.log(myset.size);
myset.add(9);
myset.delete(2);
myset.has(2); //TRUE
//removes all of the duplicates
```
### Maps
Maps are objects that store key, value pairs. In the case of maps, both the keys and values can be of any type.
```Javascript
let map2d=[["a","b"],[1,2]];
let myMap= new Map(map2d);
console.log(myMap);
myMap.set("c",3);
myMap.get("c");
```

## Conditionals
### If statement
### Switch statements
### For loop
### While loop

## Functions

### Defining functions
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
### Scope
### Closures
### Prototypes



## ES6 concepts
### Template literals
### Destructing Objects and Arrays
### Object literals
### For of loop
### Spread operator
### Rest operator
### Arrow functions
### Default Params
### Includes()
### Let and Const
### Import and Export
### padStart() and padEnd()
### Classes
### Trailing commas
### Async and Await
### Sets
### Promises
### ES modules


## Working With the DOM
### Select HTML elements
### Manipulate HTML elements
### DOM traversal
### Adding and Removing elements
### Creating elements and other nodes
### DOM Events

## Web APIs

### Selector API
### Geolocation
### Web storage
### Web workers








