# Operators

An [`operator`](https://developer.mozilla.org/en-US/docs/Glossary/Operator) is a mathematical symbol that produces a result based on two values (or variables). In the following table, you can see some of the simplest operators, along with some examples to try in the JavaScript console.

| Operator                              | Explanation                                                                                                                                                                                                             | Symbol(s)     | Example                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Addition                              | Add two numbers together or combine two strings.                                                                                                                                                                        | `+`           | <p><code>6 + 9;</code><br><code>'Hello ' + 'world!';</code></p>                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Subtraction, Multiplication, Division | These do what you'd expect them to do in basic math.                                                                                                                                                                    | `-`, `*`, `/` | <p><code>9 - 3;</code><br><code>8 * 2; // multiply in JS is an asterisk</code><br><code>9 / 3;</code></p>                                                                                                                                                                                                                                                                                                                                                                                                           |
| Assignment                            | As you've seen already: this assigns a value to a variable.                                                                                                                                                             | `=`           | `let myVariable = 'Bob';`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Equality                              | This performs a test to see if two values are equal. It returns a `true`/`false` (Boolean) result.                                                                                                                      | `===`         | <p><code>let myVariable = 3;</code><br><code>myVariable === 4;</code></p>                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Not, Does-not-equal                   | This returns the logically opposite value of what it precedes. It turns a `true` into a `false`, etc.. When it is used alongside the Equality operator, the negation operator tests whether two values are _not_ equal. | `!`, `!==`    | <p>For "Not", the basic expression is <code>true</code>, but the comparison returns <code>false</code> because we negate it:</p><p><code>let myVariable = 3;</code><br><code>!(myVariable === 3);</code></p><p>"Does-not-equal" gives basically the same result with different syntax. Here we are testing "is <code>myVariable</code> NOT equal to 3". This returns <code>false</code> because <code>myVariable</code> IS equal to 3:</p><p><code>let myVariable = 3;</code><br><code>myVariable !== 3;</code></p> |

{% hint style="info" %}
**Note:** Mixing data types can lead to some strange results when performing calculations. Be careful that you are referring to your variables correctly, and getting the results you expect. For example, enter `'35' + '25'` into your console. Why don't you get the result you expected? Because the quote marks turn the numbers into strings, so you've ended up concatenating strings rather than adding numbers. If you enter `35 + 25` you'll get the total of the two numbers.
{% endhint %}