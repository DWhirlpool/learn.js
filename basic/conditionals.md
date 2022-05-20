# Conditionals

[Functions](https://developer.mozilla.org/en-US/docs/Glossary/Function) are a way of packaging functionality that you wish to reuse. It's possible to define a body of code as a function that executes when you call the function name in your code. This is a good alternative to repeatedly writing the same code. You have already seen some uses of functions. For example:

```
let iceCream = 'chocolate';
if(iceCream === 'chocolate') {
  alert('Yay, I love chocolate ice cream!');
} else {
  alert('Awwww, but chocolate is my favorite...');
}
```

The expression inside the `if( ... )` is the test. This uses the identity operator (as described above) to compare the variable `iceCream` with the string `chocolate` to see if the two are equal. If this comparison returns `true`, the first block of code runs. If the comparison is not true, the second block of code—after the `else` statement—runs instead.
