1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```
//when a function dosent return a value the output is undefined therfore the first "sum" function returnes a+b as the result where as the second will return undefined.

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.
//the first function will return a value such as sum of two numbers or strings and the second function will have undefined as the output.
3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
//36 the first function will acept 2 parameters add result in adding the first 2.
4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
//yes we can store the value of the first `sum` function in a variable named `add` as it returns a value.

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
// function sayHello(name){
  return (`Hello + " "+ ${name}`);
}
sayHello('Arya')
6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
//'Hello, Jhon' 
7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // Output 1 //"John"

showMessage(); // Output 2// "Hello, John"

alert(userName); // "John"
```

8. What is a Anonymous Function give example of three functions.
//Anonymous Function is Function that dosnt contain a name
for example:
let Add =function(a, b){
  return a+b;
}
let sub =function(a, b){
  return a-b;
}
let mul=function(a, b){
  return a*b;
}

9. Can function declaration be a Anonymous Function? Explain
yes function declaration can be a Anonymous 
for example 
const sqr=(n)=>n*n;

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.
5 example of good naming convention for defining a function are 
getSum()
createblock()
checkAddress()
updateRow()
manX()

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
