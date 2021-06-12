Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

Example:

```js
function hello() {
  var username = "Arya";
}
console.log(useranme); //  ReferenceError
```

In above code we are looking for the variable named `usename`. There is no variable named `username` in the global scope. The variable is inside the function named `hello` and we can't access the variable defined inside a function from outside.

The above code will throw an error `Reference Error username is not defined`.

2. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
{
  const username = "Arya";
}
console.log(useranme); // Reference Error
```

In above code we are looking for the variable named `usename`. There is no variable named `username` in the global scope. The variable is inside the unnamed object and we can't access the variable defined inside an object from outside without referencing the object itself.

The above code will throw an error `Reference Error username is not defined`.

3. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  let username = "Arya";
}
console.log(useranme); // Reference Error
```

In above code we are looking for the variable named usename. There is no variable named username in the global scope. The variable is inside an if statement and we can't access the variable defined inside a statement from outside.

The above code will throw an error Reference Error username is not defined.

4. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  var username = "Arya";
}
console.log(useranme); // output
```

5. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = "John";
if (true) {
  var username = "Arya";
}
console.log(useranme); // SyntaxError
```

In above code we are looking for the variable named usename. There is one variable named username in the global scope and also another variable username declared within the if statement, since it has been declared using var keyword, it will have a global scope and we can not declare two variables with same name and same scope . So here the variable username is being declared two times hence will throw an error.

The above code will throw an error Sytax Error 'Identifier' username has already been declared.

6. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = "John";
if (true) {
  let username = "Arya";
}
console.log(useranme); // Syntex Error
```

In above code we are looking for the variable named usename. There is one variable named username in the global scope and also another variable username declared within the if statement, since it has been declared using let keyword it will have a global scope and we can not declare two variables with same name and same scope . So here the variable username is being declared two times hence will throw an error.

The above code will throw an error Sytax Error 'Identifier' username has already been declared.

7. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = "John";
function sayHello() {
  let username = "Arya";
}
sayHello();
console.log(useranme); // output
```

8. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (var i = 0; i < 10; i++) {
  console.log(i, "First"); // 0-9, First (10 times)t
}
console.log(i, "Second"); // 10 "second"
```

In the above code we looking for variable i which has been declared using var inside the for loop, the console.log function inside the loop will run 10 times and will log i form 0 to 9 as well as First 10 times. Since the variable i has been declared using var it will have a global scope, and can be accessed from outside the loop as well.

9. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (let i = 0; i < 10; i++) {
  console.log(i, "First"); // First (9 times)
}
console.log(i, "Second"); //  ReferenceError: i is not defined
```
