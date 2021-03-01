# Table of Contents
1. [Datatypes](#1-datatypes)
2. [Strings](#2-strings)
3. [Objects](#3-objects)
4. [JavaScript Object Notation (JSON)](#4-javascript-object-notation-json)
5. [Destructuring](#5-destructuring)
6. [Asynchronous JavaScript](#6-asynchronous-javascript)
7. [Modules](#7-modules)


## 1. Datatypes
The primitive data types in JavaScript are string, number, function, boolean, object, undefined, symbol, and null. Since JavaScript is dynamically typed, you don’t need to specify the variable type in the declaration. You can declare variables using **let** and **var**. Similarly, you can declare constants using **const**`.
### let vs. var
Generally, it is better to use let rather than var. This is because var has problems with variable hoisting and scoping.


## 2. Strings
In JavaScript, you can declare strings using either **"** or **'**. Additionally, if the string you want to declare is long and would be better formatted to span multiple lines, you can declare it using **\`**.


The `+` symbol is overloaded in JavaScript. It can be used for both addition and string concatenation. However, it is more preffered to format strings using `${}` instead. This can only be done inside strings wrapped in ``.


## 3. Objects
Objects are a way to package multiple attributes and methods under one variable. Attributes and methods, which are also called values, can be accessed using a key. This is called a key-value pair. In order to access an objects values, you can access it directly (`object.key`) or by indexing the object using the key (`object['key']`).


## 4. JavaScript Object Notation (JSON)
JSON is very similar to the syntax of JavaScript objects. The only difference is the all strings and keys must be wrapped in **"**. Additionally, JSON cannot have functions as values.


## 5. Destructuring
Destructuring is used to quickly store values of an object or elements of an array into variables. When destructuring arrays, **[]** is used while **{}** is used for objects. For arrays, the order of the elements reflect on the order of the declared variables. For objects, the variables must have the exact same name as the keys of the object.


## 6. Asynchronous JavaScript
JavaScript can be told not to wait for a certain line of code to finish executing before moving on. This can be done using **callbacks**, **promises**, or **async await**. Promises can be given to an asynchronous call. Promises can either **resolve** or **reject** meaning it either succeeded or ran into an error. Either way, it a corresponding action can be performed using `.then()` or `.catch()` respectively. Async await, is another way to handle promises. By using await in an async function, JavaScript will wait the value in await is properly returned. This requires a `try() {} catch() {}` block because it has no other way to handle a rejection.


## 7. Modules
Modules are a way to package functions and values so that multiple files can share them. This is done by setting `module.exports` to your desired function, value, or object containing both functions and values.