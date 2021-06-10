1. What does thread of execution means in JavaScript?

Ans. When we want to execute the peace of code . Javascript engine take the code and execute the code line buy line is theread of execution means in Javascript

2. Where the JavaScript code gets executed?

Ans. Javascript Engine

3. What does context means in Global Execution Context?

Ans. It means that the enirvernment in which we are executing the code

4. When do you create a global execution context.

Ans. Whenever we Executive the code . the javascript engine will create a Globle Execution context for us.

5. Execution context consists of what all things?

Ans. Execution context contain a section which for storing data . it is also call memory

6. What are the different types of execution context?

Ans . 1. Globle Execution Context 2. Function Execution Context

7. When global and function execution context gets created?

Ans. 1. Globle Execution Context gets created whenever we run any code in JavaScript for the first time.
Function Execution Context gets created whenever we execute any function.

8. Function execution gets created during function execution or while declaring a function.

Ans. Function Executon get created during function execution and get deleted when it returns a value.

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.

```js
var user = "Arya";

function sayHello() {
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./)

```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount) {
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-name.jpg)

```js
var age = 21;

function customeMessage(userAge) {
  if (userAge > 18) {
    return `You are an adult`;
  } else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)
