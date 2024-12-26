# Unhandled Promise Rejection in React Native Fetch

This repository demonstrates a common issue in React Native development: unhandled promise rejections. The `bug.js` file contains a component that fetches data using the `fetch` API.  If the fetch fails, a promise rejection occurs which is not properly handled, leading to potential crashes or silent failures.

The `bugSolution.js` file provides a solution by using a `try...catch` block within the `async` function to handle potential errors gracefully.