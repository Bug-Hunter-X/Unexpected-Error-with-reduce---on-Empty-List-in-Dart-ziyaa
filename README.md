# Dart Reduce() Method Error with Empty List

This repository demonstrates an unexpected behavior of the `reduce()` method in Dart when applied to an empty list. The `reduce()` method attempts to combine elements of a list using a provided function.  When the list is empty, it throws an `Unsupported error: Empty list` exception.

The `bug.dart` file shows the code causing the error, and `bugSolution.dart` provides a solution to handle this case gracefully.

## How to Reproduce

1. Clone this repository.
2. Run `bug.dart` using a Dart compiler.
3. Observe the error.

## Solution

The provided solution in `bugSolution.dart` uses a conditional check before calling `reduce()` to prevent the error.  This makes the code more robust.