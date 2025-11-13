
# TintLog

You can colorize console messages.
Colors -> Green - Red - Yellow
Info is yellow.
Erro is red.
Seccess is green.




## Installation

Install the package with go

```bash
  go get github.com/gootibi/tintlog
```
    
## Usage/Examples

```golang
package main

import "github.com/gootibi/tintlog"

func main() {
	tintlog.Info("This is the info")
	tintlog.Error("This is the error")
	tintlog.Success("This is the success")
}
```


## Authors

- [@gootibi](https://www.github.com/gootibi)

