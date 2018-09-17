### Quiz

Check your understanding so far. Make sure to play the part of *Engine* and have a "conversation" with the *Scope*:

```js
function foo(a) {
	var b = a;
	return a + b;
}

var c = foo( 2 );
```

1. Identify all the LHS look-ups (there are 3!).

2. Identify all the RHS look-ups (there are 4!).

### Answers

1.  * c will be the the first lookup 
    * then a = 2 as c has been run 
    * then b will run as a exists.

2.  * foo(2 will be found first
    * = a will then be found now that we have a
    * then a and b as the return executes.
