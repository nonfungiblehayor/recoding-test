# Fishandchips

## Instructions
Write a function called FishAndChips() that takes an int and returns a string.
- If the number is divisible by 2, print fish.
- If the number is divisible by 3, print chips.
- If the number is divisible by 2 and 3, print fish and chips.
- If the number is negative return error: number is negative.
- If the number is non divisible by 2 or 3 return error: non divisible.

---

## Expected Function

```go
func LastWord(s string) string{

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
	fmt.Print(piscine.LastWord("this        ...       is sparta, then again, maybe    not"))
	fmt.Print(piscine.LastWord(" lorem,ipsum "))
	fmt.Print(piscine.LastWord(" "))
}
```

## Output
```go
$ go run . | cat -e
not$
lorem,ipsum$
$
$
```