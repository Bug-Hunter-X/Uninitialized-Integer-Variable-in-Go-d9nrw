# Uninitialized Integer Variable in Go

This repository demonstrates an uncommon error in Go related to the use of uninitialized integer variables.  Uninitialized variables can lead to unexpected behavior and make your code less reliable. The provided code demonstrates this behavior and its solution.

## Bug

The `bug.go` file contains a simple Go program with an uninitialized integer variable `i`.  When the program runs, the value of `i` will be unpredictable (often 0, but not guaranteed).  This can lead to subtle and hard-to-debug problems.