# Hello
```
go env -w GOPATH=$(pwd)
ln -s `pwd`/hello $(go env GOPATH)/src
go run main.go
```