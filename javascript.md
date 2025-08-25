`What are Pure and Impure Functions?`

Pure function is a function which does not modifies the external data. It is predictable. Because, sum is a function
whose sole purpose is to add the values and it returns you a single value. It gives the same output for the same input.
whereas impure function is a function which modifies the external data and it is not predictable as external value could
be anything that is used in it.

Example of Impure Functions

```javascript
let x = 0;
function func (x) = {
   x++; // any other code
  }
```
