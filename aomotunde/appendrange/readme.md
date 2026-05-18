# Appendrange

## Instructions
Write a function that takes an int min and an int max as parameters. The function should return a slice of ints with all the values between the min and max.

Min is included, and max is excluded.

If min is greater than or equal to max, a nil slice is returned.

make is not allowed for this exercise.


---

## Expected Function

```go
func AppendRange(min, max int) []int {

}
```

## Usage
Here is a possible program to test your function:
```go
package main

import (
	"fmt"
)

func main() {
	fmt.Println(AppendRange(5, 10))
	fmt.Println(AppendRange(10, 5))
}
```

## Output

```go
$ go run . | cat -e
$ go run .
[5 6 7 8 9]
[]
$