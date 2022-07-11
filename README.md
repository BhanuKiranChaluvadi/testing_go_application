# testing_go_application
Part of a plural sight tutorial - Testing go application

```bash
$ go help test
$ go help testflag
$ cd messages && go test -v
$ cd messages && go test -run Greet
$ go test -v ./...
$ go test -cover ./...
$ go test -coverprofile cover.out && go tool cover -func cover.out
$ go tool cover -html cover.out
$ go test -coverprofile count.out -covermode count
$ go tool cover -html count.out
```