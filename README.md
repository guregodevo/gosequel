gosequel
========

A thin SQL layer written in Go


##Quick Example

```go
//main.go
package main

import "github.com/guregodevo/gosequel"

func main() {
    db := gosequel.DataB{"postgres", "localhost", "postgres", "postgres", "mydb", nil}
	fmt.Printf("SQL Database - %v\n", db.Url())


}
```

And run with:

```
go run main.go
```

## Installing

### Using *go get*

    $ go get github.com/guregodevo/gosequel

After this command *gosequel* is ready to use. Its source will be in:

    $GOROOT/src/pkg/github.com/guregodevo/gosequel

You can use `go get -u -a` to update all installed packages.
