# printcomb2

## Instructions


Write a function that prints in ascending order and on a single line: all possible combinations of two different two-digit numbers.

These combinations are separated by a comma and a space.
---

## Expected Function

```go
func PrintComb2() {

}
```

## Usage
Here is a possible program to test your function:
```go
package main

import "piscine"

func main() {
	piscine.PrintComb2()
}

```

## Output

```go
$ go run . | cat -e
00 01, 00 02, 00 03, ..., 00 98, 00 99, 01 02, 01 03, ..., 97 98, 97 99, 98 99$
$