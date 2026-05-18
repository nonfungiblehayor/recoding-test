# Chunk

## Instructions
Write a function CountAlpha() that takes a string as an argument and returns the number of alphabetic characters in the string.
-   If the size is 0 it should print a newline ('\n').
---

## Expected Function

```go
func Chunk(slice []int, size int) {

}
```

## Usage
Here is a possible program to test your function:
```go
package main

func main() {
	Chunk([]int{}, 10)
	Chunk([]int{0, 1, 2, 3, 4, 5, 6, 7}, 0)
	Chunk([]int{0, 1, 2, 3, 4, 5, 6, 7}, 3)
	Chunk([]int{0, 1, 2, 3, 4, 5, 6, 7}, 5)
	Chunk([]int{0, 1, 2, 3, 4, 5, 6, 7}, 4)
}

```

## Output

```go
$ go run .
[]

[[0 1 2] [3 4 5] [6 7]]
[[0 1 2 3 4] [5 6 7]]
[[0 1 2 3] [4 5 6 7]]
$