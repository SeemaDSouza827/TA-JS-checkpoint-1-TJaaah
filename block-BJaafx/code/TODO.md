1. Using loops take 10 inputs from user and find the average of all the numbers.
function avg(n){
  let total=0;
  for(let i = 1; i <= n; i++){
  let num = +prompt(`Enter the ${i}th Number`);
    total += num;
  }
  return(`avg is ${total/n}`);
}
avg(5);

2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}//println is not defined
```

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
function getEvenSum(max=10){
  let sum=0;
  for(let i = 1; i <= max; i++){
    if(i%2 ===0){
      sum+=i;
    }
  }
    return(`${sum}`);
}
getEvenSum()

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
function getOddSum(max=10){
  let sum=0;
  for(let i = 1; i <= max; i++){
    if(i%2 !==0){
      sum+=i;
    }
  }
    return(`${sum}`);
}
getOddSum()
5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

function getProductOfDigits(num){
  if (num<0){
    let str= string(num);
    let product=1;
    for(let i=0; i < str.legth; i++){
      product *= str[i];
    }
  return product;
  }
  else{
    return(`not a valid input`);
  }
}
getProductOfDigits(2341)

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // 'Bigger than 5'
check(1); // 'Smaller than 5'
check(5); // 5
//each condition is written seperately only if the conditin is satisfied that perticular return statement will be executed. 
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // 'You are arya'.
getOutput('John'); //'You are john'.
getOutput(); // 'Who are you'.
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // 'You are arya'.
getOutput('John'); // 'You are john'.
getOutput(); // 'Who are you'.
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
 A  function can  have multiple return statement in case of conditional staements
 for example:
 if else
 
10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
while — loops through a block of code once; then the condition is evaluated. If the condition is true, the statement is repeated as long as the specified condition is true. 
for — loops through a block of code until the counter reaches a specified number.