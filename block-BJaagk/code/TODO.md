1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
```
let percentage = function percentage (marks, total) {
  return (marks * 100) / total;
}

let percentage = function (marks, total) {
  return (marks * 100) / total;
}

let percentage = (marks, total) => {
  return (marks * 100) / total;
}

let percentage = (marks, total) => (marks * 100) / total;



2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
```
function decleration

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

function expression
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
function expression
```


```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};

function expression
```

```js
let percentage = (marks, total) => (marks * 100) / total;

function expression
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

<!-- Function Expression allows us to create an anonymous function which doesn't have any function name which is the main difference between Function Expression and Function Declaration. -->

4. Why is a function call an expression in JavaScript?

<!-- A function call expression is used to execute a specified function with the provided arguments -->

5. Write VALID and INVALID next to each example below with the reason.



```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // valid 5
five = add; // valid
five = five(10, 11); // valid
five = function () {
  return 'Hello';
}; // valid
```

6. What is the difference between function definition and function call? Explain with an example.

<!-- function call / execution = we use without parentheses
function refrence = we use parentheses -->

7. What is the similarities between function definition and function call?

<!-- A function is a piece of code which enhanced the reusability and modularity of your program. It means that piece of code need not be written again. A function call means invoking or calling that function. Unless a function is called there is no use of that function -->


8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}
valid

hello.user = 'Sam'; // valid
```

9. What is higher order function explain with an example.


<!-- A higher order function is a function that takes a function as an argument, or returns a function . Higher order function is in contrast to first order functions, which don't take a function as an argument or return a function as output. -->

10. Explain what is callback function. Why you can pass a function inside a function?

<!-- A callback function is a function passed into another function as an argument, which is then invoked inside the outer function to complete some kind of routine or action -->

