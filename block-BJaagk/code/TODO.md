1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here

let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

let percentage = percentage(marks, total) {
  return (marks * 100) / total;
};

let percentage = percentage(marks, total)=> {
  return (marks * 100) / total;
};

let percentage = (marks, total)=> (marks * 100) / total;


```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Function Declartion
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

// Function Expression
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};

//Function Expression
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};

//Function Expression with Arrow Function
```

```js
let percentage = (marks, total) => (marks * 100) / total;

// Arrow Function
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

Ans - An Expression is anything that results into a value. because it results into what we want from that particular function.

```js
let addBoth = function (a, b) {
  return a + b;
};
```

4. Why is a function call an expression in JavaScript?

 Ans- Because it result into value

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Valid
five = add; // Valid
five = five(10, 11); // Valid
five = function () {
  return "Hello";
}; // Valid
```

6. What is the difference between function definition and function call? Explain with an example.

Ans - Function defination means that function is giving steps that will follow when ever it is excute and function call means the execute the function

7. What is the similarities between function definition and function call?

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log("Hello World!");
}

hello.user = "Sam"; // valid
```

9. What is higher order function explain with an example.

Ans: A function that accepts a function definition as an argument is known as Higher order function.

```js
function add(a, b) {
  return a + b;
}
function average(a, b) {
  return add(a, b) / 2;
}
```

10. Explain what is callback function. Why you can pass a function inside a function?
