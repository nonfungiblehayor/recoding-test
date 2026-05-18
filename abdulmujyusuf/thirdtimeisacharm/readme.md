# Thirdtimeisacharm

## Instructions
Write a function ThirdTimeIsACharm() that takes a string as an argument and returns another string with every third character.
- Return the output followed by a newline \n.
- If the string is empty, return a newline \n.
- If there is no third character, return a newline \n.
---

## Expected Function

```go
func ThirdTimeIsACharm(str string) string {

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
	fmt.Print(ThirdTimeIsACharm("123456789"))
	fmt.Print(ThirdTimeIsACharm(""))
	fmt.Print(ThirdTimeIsACharm("a b c d e f"))
	fmt.Print(ThirdTimeIsACharm("12"))
}
```

## Output

```go
$ go run . | cat -e
369$
$
b e$
$