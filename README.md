# React useEffect Hook: Missing Dependency

This repository demonstrates a common error in React's `useEffect` hook and its solution.

The `bug.js` file showcases an example where a dependency (`count`) is missing from the `useEffect`'s dependency array. This leads to unexpected re-renders and potential performance problems.

The solution, provided in `bugSolution.js`, correctly includes the `count` dependency, ensuring the effect runs only when the `count` value changes.

## How to reproduce

1. Clone the repository
2. Navigate to the directory
3. Run `npm install` to install dependencies
4. Run `npm start` to start the development server
5. Observe the console logs and the behavior of the counter.

## Solution

The correct implementation of the `useEffect` hook ensures that the effect only executes when the value of `count` is updated, preventing unnecessary re-renders and improving performance.