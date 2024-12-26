# Unnecessary Re-renders in React useEffect Hook

This repository demonstrates a common issue with the React `useEffect` hook: unnecessary re-renders caused by missing dependencies in the dependency array. The `useEffect` hook in `bug.js` is designed to log messages to the console but ends up executing on every render instead of only when the count changes.

The solution in `bugSolution.js` demonstrates the correct way to add the dependency to fix the issue. 