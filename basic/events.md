# Events

Real interactivity on a website requires event handlers. These are code structures that listen for activity in the browser, and run code in response. The most obvious example is handling the [click event](https://developer.mozilla.org/en-US/docs/Web/API/Element/click\_event), which is fired by the browser when you click on something with your mouse. To demonstrate this, enter the following into your console, then click on the current webpage:

```
document.querySelector('html').addEventListener('click', function() {
  alert('Ouch! Stop poking me!');
});
```

There are many ways to attach an event handler to an element. Here we select the [`<html>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/html) element. We then call its [`addEventListener()`](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener) function, passing in the name of the event to listen to (`'click'`) and a function to run when the event happens.

Note that

```
document.querySelector('html').addEventListener('click', function() {
  alert('Ouch! Stop poking me!');
});
```



is equivalent to

```
let myHTML = document.querySelector('html');
myHTML.addEventListener('click', function() {
  alert('Ouch! Stop poking me!');
});
```

It's just shorter.

The functions we just passed to `addEventListener()` here are called _anonymous functions_, because they don't have a name. There's an alternative way of writing anonymous functions, which we call an _arrow function_. An arrow function uses `() =>` instead of `function ()`:

```
document.querySelector('html').addEventListener('click', () => {
  alert('Ouch! Stop poking me!');
});
```
