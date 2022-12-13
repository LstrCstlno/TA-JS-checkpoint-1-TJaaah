1. Using loops take 10 inputs from user and find the average of all the numbers.
```js
let sum = 0;
let arr = num[i];
for(let i=0; i<=10;i++){
num[i] = +prompt("ENter a number")
sum += num[i]
}
average = sum/10;
alert(average);
```

2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.

```js
function getEvenSum(max){
  var max = 10
  var total = 0;
  for (let i = 0; i <= max; i++){
    if(i % 2 === 0)
     total += i;
  }
  return total;
}
4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
function odd(max){
  var max = 10
  var total = 0;
  for (let i = 0; i <= max; i++){
    if(i % 2 === 1)
     total += i;
  }
  return total;
}

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

function getProductofDigits(num){
  if(num<0)
  return "not a valid input";
  else
  return 
}

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

check(10); // bigger than 5 (because 10 is > 5)
check(1); // smaller than 5 (because 1 < 5)
check(5); // 5 (since num isnt greater or lesser than 5, num will be 5)
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // 'You are arya' (since name === 'Arya')
getOutput('John'); // 'You are john'(since name === 'john')
getOutput(); // 'Who are you' ('since name is blank)
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // "You are arya" will be the output but itll still return "Who are you"
getOutput('John'); // "You are john" will be the output but itll still return "Who are you"
getOutput(); // "Who are you""
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
Yes a function can have multiple return statements depending on the conditions of excecution.
Example 
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
```
from here wee see depending on input if the number is > 5 we have one return statment else we have less than 5  or 5 itself

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
for loop is used when you know the number of iterations ahead of time, while a while loop is used when you donno the number of iterations and want to keep excecuting as long as the conditions are true.

example for for loop 
list of even numbers 
```js
function even(num){
  for(let i=0;i<num;i++){
    if(i %2 == 0)
console.log(i);
  }
}
```