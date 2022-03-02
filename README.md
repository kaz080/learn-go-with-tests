# Hands-on "Learn Go with tests"

https://quii.gitbook.io/learn-go-with-tests/


Click the button below to start a new development environment:

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/kaz080/learn-go-with-tests)

## Setup

To install go for macOS,

    brew install go
    go version

To test all,

    go test -v ./...

To use go tools such as godoc, add following to your rc file.

    export GOPATH=$HOME/go
    export PATH=$GOPATH/bin:$PATH

To see documents,

    go get golang.org/x/tools/cmd/godoc
    godoc -http :8080
    open http://localhost:8080/pkg/hello
