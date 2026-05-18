# Gcd

## Instructions
Write a function that takes two uint representing two strictly positive integers and returns their greatest common divisor. If any of the input numbers is 0, the function should return 0.

---

## Expected Function

```go
func Gcd(a, b uint) uint {

}
```

## Usage
Here is a possible program to test your function:
```go
package main

import (
	"fmt"
	"piscine"
)

func main() {
	fmt.Println(piscine.Gcd(42, 10))
	fmt.Println(piscine.Gcd(42, 12))
	fmt.Println(piscine.Gcd(14, 77))
	fmt.Println(piscine.Gcd(17, 3))
}
```

## Output
```go
$ go run .
2
6
7
1
$
```