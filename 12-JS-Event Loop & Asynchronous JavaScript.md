````js

Day 20: Event Loop & Asynchronous JavaScript (H)

1. Understanding the Event Loop

   JavaScript is single-threaded, meaning it executes one operation at a time. The event loop manages the execution of multiple operations by handling asynchronous events, ensuring non-blocking behavior. It continuously checks the call stack and task queues, executing tasks from the queues when the call stack is empty.

2. Call Stack & Web APIs

   - Call Stack: Manages function execution in a Last-In-First-Out (LIFO) order. When a function is called, it's added to the stack; once executed, it's removed.

   - Web APIs: Provided by the browser to handle asynchronous operations (e.g., setTimeout, DOM events, HTTP requests). These operations run outside the call stack, allowing JavaScript to remain non-blocking.

3. Microtasks vs. Macrotasks

   - Microtasks: High-priority tasks executed immediately after the current operation completes and before any macrotasks. Examples include Promise callbacks and MutationObserver callbacks.


     console.log('Script start');

     setTimeout(() => {
       console.log('setTimeout'); // Macrotask
     }, 0);

     Promise.resolve().then(() => {
       console.log('Promise'); // Microtask
     });

     console.log('Script end');


     Output:
     ```
     Script start
     Script end
     Promise
     setTimeout
     ```

   - Macrotasks: Lower-priority tasks executed after microtasks. Examples include setTimeout, setInterval, and I/O events.


     console.log('Script start');

     setTimeout(() => {
       console.log('setTimeout 1'); // Macrotask
     }, 0);

     setTimeout(() => {
       console.log('setTimeout 2'); // Macrotask

     }, 0);

     console.log('Script end');


     Output:
     Script start
     Script end
     setTimeout 1
     setTimeout 2


   Execution Order Example:


   console.log('Start');

   setTimeout(() => console.log('Macrotask 1'), 0);

   Promise.resolve().then(() => console.log('Microtask 1'));

   setTimeout(() => console.log('Macrotask 2'), 0);

   Promise.resolve().then(() => console.log('Microtask 2'));

   console.log('End');
````
