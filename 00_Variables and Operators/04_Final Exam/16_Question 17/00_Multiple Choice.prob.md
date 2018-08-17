>>Given the following code segment, what is the value of varTwo?

```
double varOne = 9.692;
int varTwo = 12;
varTwo = (int)varOne;
```

<<

( ) 12 {{Incorrect because this is the initial value of <code>varTwo</code>, <code>(int)varOne</code> does not result in 12.}}
( ) 10 {{Incorrect because Java does not round when converting from a <code>double</code> to an <code>int</code> value.}}
(x) 9 {{Correct because a <code>double</code> truncates the digits after the decimal when it is converted into an <code>int</code> value.}}
( ) 9.692 {{Incorrect because this is the value of <code>varOne</code>, not <code>varTwo</code>.}}
( ) 12.692 {{Incorrect because <code>varTwo</code> is declared and initialized as a integer.}}

||Is <code>varTwo</code> an integer or a double? ||
