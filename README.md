# TypeScript: Handling 'undefined' in Union Types

This repository demonstrates a common TypeScript error related to handling 'undefined' values in union types.  The `printName` function accepts either a string or null. While it correctly handles `null`, it throws a type error when `undefined` is passed.

The solution showcases how to explicitly handle 'undefined' using optional chaining or type narrowing.