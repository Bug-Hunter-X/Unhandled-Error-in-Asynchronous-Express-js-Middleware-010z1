## Unhandled Error in Asynchronous Express.js Middleware
This repository demonstrates a common error in Node.js applications using Express.js: unhandled errors within asynchronous middleware. The code simulates an asynchronous operation that randomly throws an error.  Without proper error handling, this leads to the server crashing.

The `bug.js` file showcases the problematic code.  The `bugSolution.js` demonstrates a corrected version using appropriate error handling.

### How to Reproduce
1. Clone the repository.
2. Run `npm install` to install Express.js.
3. Run `node bug.js` to observe the error (it may take a few attempts due to the random nature of the error). 
4. Run `node bugSolution.js` to see the error handled gracefully.

This example highlights the importance of robust error handling, especially in asynchronous operations within Node.js.