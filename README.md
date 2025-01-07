# React useEffect Infinite Loop Bug

This repository demonstrates a common bug in React involving the `useEffect` hook that can lead to an infinite rendering loop.  The issue arises from incorrectly managing the dependency array of the `useEffect` hook, causing the effect to re-run unnecessarily.

## Bug Description
The `bug.js` file contains a component that uses `useEffect` to log the current count to the console. However, the `count` variable is not included in the dependency array, resulting in an infinite loop.