# Hello World TDD with golang

This is basic hello world app. Use Makefile Commands.  Can follow up belowings;

## Makefile contents
```
bench:
	go test -bench=.
cover:
	go test -cover
race:
	go test -race
```
# Example some executable commands and meanings
Benchmarking:  ```make bench```
Test coverage: ```make cover```
Race condition identification for gorutines ```make race```
Lots more! Run go test --help

# Files

- Makefile
- hello.go
- hello_test.go
