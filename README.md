# Dart Reduce Method and Empty Lists

This repository demonstrates a common error encountered when using the `reduce` method in Dart with an empty list. The `reduce` method requires at least one element in the list to operate correctly. Attempting to use it on an empty list will result in a runtime exception.

The `bug.dart` file shows the problematic code, while `bugSolution.dart` provides a solution using an optional check for an empty list.