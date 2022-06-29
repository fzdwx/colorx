# colorx

the golang console color wrapper

## Install

```shell
go get github.com/fzdwx/colorx
```

## Showcase

```go
package main

import (
	"fmt"
	"github.com/fzdwx/colorx"
)

func main() {
	fmt.Println(colorx.Cyan("hello world"))
	fmt.Println(colorx.DarkGray("who are you?"))
	fmt.Println(colorx.Blue("i'm fine,think you!"))
}
```