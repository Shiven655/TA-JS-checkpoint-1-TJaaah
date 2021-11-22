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
Ans. first function will add the the two number and give the output, and the second sum will log the sum.

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.
Ans.first+second.

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
Ans. "122435" , here parametres are not declared as Numbered value so it will return as String value.

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
Ans. Yes we can store the sum function in a variable named 'add'

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
Ans. function sayHello(name=Arya){
  return ("hello name")
}
6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
Ans. "Hello, John".
7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // Output 1 John

showMessage(); // Output 2 "Hello, John"

alert(userName); // Output 3 John
```

8. What is a Anonymous Function give example of three functions.
Ans. Anonymous function is that typw of functon that has no name or we we can say that without any name.
example: var hello = function(){
  console.log("Hello world")
}
hello();

9. Can function declaration be a Anonymous Function? Explain
Ans. Yes function declaration be a Anonymous Function , whenever we create a function without any name it is called anonymous function.

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value, // getSum
"calc…" – calculate something, // calcTotal
"create…" – create something,   // createTable
"check…" – check something and return a boolean, etc. //checkTrueFalse
```
