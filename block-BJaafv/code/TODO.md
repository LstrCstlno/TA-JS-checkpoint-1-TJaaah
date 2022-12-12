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
the first funtion returns the sum of the equation which can be further used in the program, whereas the second function just excecutes the problem in console without returning any value

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.
the value of first will be the value of the sum(a,b) whereas the value of second will be undefined ince there is no return value.


3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
the output will be 36 i.e the value of a and b will be taken and solved, since c is undefined, 35 will be undefined and hense ignored.

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
yes we can since the first function has a return value, we can store that value in any variable in this case add.

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
```js
function sayHello(name){
  return `Hello ${name}`;
}
```
6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
'Hello, John'

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // John

showMessage(); // 'Hello, John'

alert(userName); // John
```

8. What is a Anonymous Function give example of three functions.
an anonymous function is a function without a name.
 ```js
 function sum(a,b){
  return a+b;
 }

//  an annonymous function would be 
let sum = function(a,b){
  return a+b;
}

let diff = function(a,b){
  return a-b;
}

let prod = (a,b) => (a*b);
```

9. Can function declaration be a Anonymous Function? Explain
no a function declaration cannot be a anoonymous function if its already named. but if its a named variable thats aassigned to the annonymous function than it is possible.

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.
1. must be userr understandBLE,
2.Must be short
3.must reveal its purpose

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
