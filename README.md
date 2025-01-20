# Go Out of Bounds Error in For Loop
This example demonstrates a common out-of-bounds error in Go when iterating over arrays or slices using a `for` loop. The incorrect loop condition `i <= len(a)` leads to an index out of bounds error because the last valid index of an array or slice is `len(a) -1`.

The `bug.go` file contains the erroneous code. The `bugSolution.go` file provides the corrected code.

## How to Reproduce
1. Save the code in `bug.go`
2. Run the code using `go run bug.go`