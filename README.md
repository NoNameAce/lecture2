# Table of Contents
## Synchronous
## Asynchronous
## new Promise

### What is synch/async code in JavaScript ?

**Syncronus** programming provides opportunities for a program to continue
running other code while waiting for a long-running task to complete. The timeconsuming task is executed in the background while the rest of the code continues to
execute.
+ most code are synchtonous
+ Synchronous code is executed line by line
+ Each line of code waits for previous line to finish.
+ 
**ASyncronus** means the code runs in a particular sequence of instructions given
in the program. Each instruction waits for the previous instruction to complete
its execution.
+ Asynchronous code is executed after a task that runs
+ Its non-blocking
+ Callback function alone do NOT make code asynchronous
+ Execution does not wait for an asynchronous task to finish its work

## How to create Asynchronous code?
There are three ways to create **Asyncronus**
1.Callbacks:
```
setTimeout(() => {
    
}, timeout);
```
2.Promise:
```
let promise = new Promise((resolve, rejected) => {
    // logic
})   
```
3.async/await:
```
async function get(example) {
    awaits//...
}
```

## Asynchronous callbacks

Asynchronous callbacks are functions passed to another function that starts executing
code in the background. Typically, when the code in the background finishes, the async
callback function is called as a way of notifying and passing on data to the callback
function that the background task is finished.

A car as itself is an object, the car has properties:

```
setInterval(() => {
    console.log(1);
}, 3000)
```
## new Promise
In JavaScript, a promiseis a good way to handle asynchronous operations. It
is used to find out if the asynchronous operation is successfully completed or
not.
The Promise() constructor takes a function as an argument. The function also
accepts two functions resolve() and reject().
If the promise returns successfully, the resolve() function is called. And, if an
error occurs, the reject() function is called.
```
let promise = new Promise((resolve, rejected) => {
    // Do somethink
})   
```
## keyword async
The async keyword transforms a regular JavaScript function into an
asynchronous function, causing it to return a Promise. The await keyword is
used inside an async function to pause its execution and wait for a Promise to
resolve before continuing.
```
async function get(example) {
    // Statement
}
```

## try/catch
The **try...catch** construct attempts to execute the statements in the try
block, and if an error occurs, executes the catch block.

try...catch works like this: code that might throw an
error is placed in a try block. If an error occurs in the
try block, the program goes to the catch block, where
you can handle the error and take the necessary
actions. However, the rest of the code continues to
execute and your application won't break.




