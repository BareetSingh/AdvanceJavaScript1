# Advance Javascript

## Discussed Advanced Concepts
- Nested function's scope
- Closures
- Currying
- this keyword
- Prototype
- Prototypal inheritance
- Class
- Iterables and Iterators
- Generators
---

## Scope
Block scope - variables declared inside a pair of curly braces cannot be accessed from outside
the block
Function scope - variables declared inside a function cannot not be accessed from outside the
function
Global scope globally scoped variables can be accessed inside a block or function

---
## Closure
In Javascript, when we return a function from another function, we are effectively returning a
combination of the function definition along with the function's scope. This would let the
function definition have an associated persistent memory which could hold on to live data
between executions. That combination of the function and its scope chain is what is called a
closure in JavaScript.

---
## Function Currying
Currying is a process in functional programming in which we transform a function with multiple
arguments into a sequence of nesting functions that take one argument at a time.
function ffa, b,c) is transformed to fla)(b)(c)
---
### [Followed this Video](https://www.youtube.com/watch?v=R9I85RhI7Cg)

