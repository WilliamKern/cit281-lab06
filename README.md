# CIT 281 Lab 06

## Overview  
Lab 06 focused on asynchronous programming in JavaScript using Promises. I learned how to define and work with Promises, including how to resolve and reject them, and how to use `.then()`, `.catch()`, and `.finally()` to create sequential logic for asynchronous operations. The lab emphasized how Promises help manage tasks that don’t complete immediately, such as simulated network delays or API calls.

## Objectives  
- Create and return a `Promise` using the `Promise` constructor  
- Use `setTimeout()` to simulate delayed asynchronous behavior  
- Chain `.then()` methods to run tasks in sequence  
- Handle errors using `.catch()`  
- Use `.finally()` for cleanup that runs regardless of outcome  
- Understand how data is passed between chained `.then()` calls

## Deliverables  
- A `.js` file demonstrating:
  - Custom `sleep()` function that returns a Promise
  - Chained Promise methods for sequential output
  - Proper error handling and final logging regardless of success or failure

## What I Learned  
This lab deepened my understanding of asynchronous programming and how Promises make complex timing and event sequencing more manageable in JavaScript. I practiced chaining actions and catching errors gracefully, which will be essential for working with real-world APIs and async functions in future projects.
