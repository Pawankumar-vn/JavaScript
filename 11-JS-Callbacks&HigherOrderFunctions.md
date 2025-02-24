```js

Day 11: Callbacks & Higher-Order Functions (H)

1. Callbacks
   setTimeout(() => {
     console.log("Executed after 1 second");
   }, 1000);
   setInterval(() => {
     console.log("Executed every 2 seconds");
   }, 2000);

2. Higher-Order Functions
   const nums = [1, 2, 3, 4, 5];
   const doubled = nums.map(n => n * 2);
   const evens = nums.filter(n => n % 2 === 0);
   const sum = nums.reduce((total, n) => total + n, 0);

3. Function Composition
   const add = x => x + 1;
   const square = x => x * x;
   const compose = (f, g) => x => f(g(x));
   const addThenSquare = compose(square, add);
   console.log(addThenSquare(4)); // 25

IMPORTANT TIPS & NOTES:
   Callbacks are used to handle asynchronous operations. Higher-order functions take functions as arguments or return functions, making your code modular. Function composition combines functions to create new functionality.
END OF NOTES
```
