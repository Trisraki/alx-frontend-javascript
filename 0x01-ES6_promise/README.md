# 0x01. ES6 Promises

## Description
This project focuses on ES6 Promises in JavaScript, covering topics such as resolving and rejecting promises, handling promise chains, using async/await, and error handling.

## Learning Objectives
- Understanding promises: how, why, and what
- Using the `then`, `resolve`, and `catch` methods
- Utilizing the `every` method of the Promise object
- Using `throw`/`try` for error handling
- Understanding the `await` operator
- Using async functions effectively

## General Requirements
- All files will be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x
- Allowed editors: vi, vim, emacs, Visual Studio Code
- All files should end with a new line
- A README.md file at the root of the project folder is mandatory
- Code files should use the `.js` extension
- Code will be tested using Jest and the command `npm run test`
- Code will be verified against lint using ESLint
- All functions must be exported

## Setup
1. Install NodeJS 12.11.x (same as in 0x00 setup)
2. Install Jest, Babel, and ESLint (same as in 0x00 setup)
3. Configuration Files (same as in 0x00 setup)

## Tasks
### 0. Keep every promise you make and only make promises you can keep
Return a Promise using the `getResponseFromAPI` function prototype.

### 1. Don't make a promise...if you know you can't keep it
Return a promise using the `getFullResponseFromAPI` function prototype based on a boolean argument.

### 2. Catch me if you can!
Append three handlers to the `handleResponseFromAPI` function for handling Promise resolution and rejection.

### 3. Handle multiple successful promises
Resolve all promises from `uploadPhoto` and `createUser` functions collectively and log their results.

### 4. Simple promise
Implement the `signUpUser` function that returns a resolved promise with a specific object.

### 5. Reject the promises
Write the `uploadPhoto` function to return a rejected promise with a specific error message.

### 6. Handle multiple promises
Write the `handleProfileSignup` function to call two other functions and return an array of resolved or rejected promises.

### 7. Load balancer
Write the `loadBalancer` function to return the value from the faster resolving promise between two promises.

### 8. Throw error / try catch
Write the `divideFunction` function to divide two numbers and throw an error if the denominator is zero.

### 9. Throw an error
Write the `guardrail` function to execute a given math function and catch any errors that occur during execution.

### 10. Await / Async (advanced)
Write the `asyncUploadUser` function to call two functions and return an object with their results, handling any failures gracefully.


