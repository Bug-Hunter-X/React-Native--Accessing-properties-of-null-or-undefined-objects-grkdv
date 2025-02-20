# React Native: Handling Null or Undefined Object Properties

This repository demonstrates a common error in React Native: attempting to access properties of an object that is null or undefined. This often arises when dealing with asynchronous data fetching, where the data might not be immediately available when a component tries to render.

The `bug.js` file shows the problematic code, which throws an error. The `bugSolution.js` file demonstrates how to safely access properties using optional chaining and the nullish coalescing operator (`??`), preventing crashes and providing a graceful fallback.