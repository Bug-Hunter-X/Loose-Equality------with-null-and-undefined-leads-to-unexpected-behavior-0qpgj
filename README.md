# Loose Equality Bug in JavaScript

This repository demonstrates a common, yet subtle, bug in JavaScript related to loose equality (==) when comparing with `null` and `undefined`.  The bug arises from the fact that `null` and `undefined` are treated differently in some comparisons.

The `bug.js` file contains the problematic code, while `bugSolution.js` provides a corrected version using strict equality (===).