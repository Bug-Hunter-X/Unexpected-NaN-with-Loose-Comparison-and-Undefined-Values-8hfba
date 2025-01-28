# JavaScript Loose Comparison Bug
This repository demonstrates a common JavaScript bug related to loose comparison (==) and handling null and undefined values.

The `bug.js` file contains a function that attempts to check for null, but fails to correctly handle undefined because of loose comparison. This results in `NaN` as the output. 

The `bugSolution.js` file demonstrates the solution using strict equality (===).