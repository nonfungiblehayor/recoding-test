# Firstword

## Instructions
Write a function that takes a string and return a string containing its first word, followed by a newline ('\n').
- A word is a sequence of characters delimited by spaces or by the start/end of the argument.

---

## Expected Function

```go
func FirstWord(s string) string {
    // ...
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
    fmt.Print(piscine.FirstWord("hello there"))
    fmt.Print(piscine.FirstWord(""))
    fmt.Print(piscine.FirstWord("hello   .........  bye"))
}
```

## Output
```go
$ go run .
hello

hello
$
```