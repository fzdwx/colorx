# colorx
我是小丑，我发现了更好用的 https://github.com/zeromicro/go-zero/blob/master/core/color/color.go

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
	fmt.Println(colorx.Cyan("cyan"))
	fmt.Println(colorx.DarkGray("dark gray"))
	fmt.Println(colorx.Blue("blue"))
	fmt.Println(colorx.Green("green"))
	fmt.Println(colorx.White("white"))
	fmt.Println(colorx.Red("red"))
	fmt.Println(colorx.Magenta("magenta"))
}
```

![image](https://user-images.githubusercontent.com/65269574/176684267-a0e26dac-0352-4f1b-9d70-df5bcf14d22a.png)
