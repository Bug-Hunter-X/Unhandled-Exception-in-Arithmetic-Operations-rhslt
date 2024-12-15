# Unhandled Exception in Arithmetic Operations

This example demonstrates a common error in decentralized applications (DApps) involving unhandled exceptions during arithmetic operations. Specifically, it showcases how a division by zero can bring down the entire application if not properly managed.

## The Problem
The `divide` function lacks robust error handling. If the divisor `b` is 0, the function throws an error, halting the execution flow and potentially crashing the application. This is especially critical in DApps where external data sources and user input can lead to unpredictable values.

## The Solution
The solution involves implementing comprehensive error handling using try-catch blocks, allowing the application to gracefully handle unexpected inputs without crashing.  Additional input validation should also be implemented to prevent invalid data from being processed.

## Running the Code
Clone this repository and run `bug.js` to observe the error. Then, examine `bugSolution.js` to see how error handling improves the application's stability and robustness.