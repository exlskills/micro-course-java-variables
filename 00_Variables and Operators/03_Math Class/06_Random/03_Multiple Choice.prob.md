>>Assume that the following variable declarations have been made.

```
double varOne = Math.random();
double varTwo;
```

Which of the following assigns a value to <code>varTwo</code> with the uniform distribution over the range 0.5 &lt;= <code>varTwo</code> &lt; 5.5?<<

( ) <pre><code>varTwo = varOne + 0.5;</code></pre> {{Incorrect because it returns a random value between 0.5 and 1.5.}}
( ) <pre><code>varTwo = varOne + 0.5 * 5.0;</code></pre> {{Incorrect because it returns a random value between 2.5 and 3.5.}}
( ) <pre><code>varTwo = varOne * 5.0;</code></pre> {{Incorrect because it returns a random value between 0 and 5.0.}}
( ) <pre><code>varTwo = varOne * 5.5;</code></pre> {{Incorrect because it returns a random value between 0 and 5.5.}}
(x) <pre><code>varTwo = varOne * 5.0 + 0.5;</code></pre> {{Correct because it accurately returns a random value between 0.5 (inclusive) and 5.5.
The process is shown below. Use the comments to guide you through each step:<br/>
<code>Math.random()</code>:             0.0 &lt;= varTwo &lt; 1.0<br/>
<code>Math.random() * 5.0</code>:       0.0 &lt;= varTwo &lt; 5.0<br/>
<code>Math.random() * 5.0 + 0.5</code>: 0.5 &lt;= varTwo &lt; 5.5}}

||<code>Math.random()</code> gives you a random number that is greater than or equal to 0 and less than 1. ||
