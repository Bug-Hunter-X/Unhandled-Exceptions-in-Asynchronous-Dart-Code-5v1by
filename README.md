# Unhandled Exceptions in Asynchronous Dart Code

This repository showcases a common error in Dart asynchronous programming: inadequate handling of exceptions during network requests and JSON decoding. The `bug.dart` file demonstrates the problematic code, while `bugSolution.dart` provides an improved version with enhanced error handling.

## Bug Description
The original code lacks comprehensive exception handling.  It only prints the error to the console, without providing more context or allowing the calling function to gracefully handle the failure. This can lead to unexpected app behavior or crashes.

## Solution
The solution introduces more robust exception handling by using `try-catch` blocks and providing more informative error messages.  It also demonstrates how to handle specific exception types for better control flow.