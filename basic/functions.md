# Functions

[Functions](https://developer.mozilla.org/en-US/docs/Glossary/Function) are a way of packaging functionality that you wish to reuse. It's possible to define a body of code as a function that executes when you call the function name in your code. This is a good alternative to repeatedly writing the same code. You have already seen some uses of functions. For example:



```
let myVariable = document.querySelector('h1');
```

```
alert('hello!');
```

These functions, `document.querySelector` and `alert`, are built into the browser.

If you see something which looks like a variable name, but it's followed by parentheses— `()` —it is likely a function. Functions often take arguments: bits of data they need to do their job. Arguments go inside the parentheses, separated by commas if there is more than one argument.

For example, the `alert()` function makes a pop-up box appear inside the browser window, but we need to give it a string as an argument to tell the function what message to display.

You can also define your own functions. In the next example, we create a simple function which takes two numbers as arguments and multiplies them:

```
function multiply(num1,num2) {
  let result = num1 * num2;
  return result;
}
```

Try running this in the console; then test with several arguments. For example:

```
multiply(4, 7);
multiply(20, 20);
multiply(0.5, 3);
```

{% hint style="info" %}
**Note:** The `return` statement tells the browser to return the `result` variable out of the function so it is available to use. This is necessary because variables defined inside functions are only available inside those functions. This is called variable scoping.
{% endhint %}
