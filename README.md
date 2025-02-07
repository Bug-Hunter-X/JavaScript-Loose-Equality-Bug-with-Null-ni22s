# JavaScript Loose Equality Bug with Null

This repository demonstrates a common bug in JavaScript related to loose equality (==) when comparing with null values.  The bug involves unexpected behavior when checking for null using loose equality instead of strict equality (===).  The solution showcases the correct use of strict equality to prevent this issue.

## Bug Description
The code contains a function that adds two numbers. However, it incorrectly handles null values using loose equality, leading to unintended null returns in cases where a strict null check is needed. 

## Bug Solution
The solution replaces the loose equality check with a strict equality (===) check. This ensures that only strict null values are considered, leading to the expected behavior.

## How to Reproduce
1. Clone this repository.
2. Open `bug.js` and run it in a JavaScript environment.
3. Observe the incorrect output of the `foo()` function with null values.
4. Open `bugSolution.js` and observe the correct output with the updated check. 