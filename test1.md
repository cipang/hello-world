## A note on loose typing ##
You might have noticed that when you define a variable with `let x` or `const x`, you don't need to specify a data type. A JavaScript variable is not tied to a specific data type in declaration, and can hold values of different data types.

```JavaScript
let x = 10;
x++;  // x is a Number
x = x.toString(2);  // binary representation
console.log(x); // x is now a String
```

## Another file is Python ##
```python
x = 10 // 1
y = [x for x in range(x)]   # List comprehension
print(y, x)
```

Below is some JS again.

```js
function add (a,b) { return a+b; }
add(1,2); // returns 3
console.log(add);
dir(add);  // shows the structure of the function object

// assign another name to the function
let f = add;
f(1,2); // returns 3. this is the same as add(1,2)
// dir(f)
```

