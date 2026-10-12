# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

Included Files:

go.mod: Declares the go module and defines its requirements for version. 
grade_calculator.go: Define grade calculator class and all of its functions/structs. 
grade_calculator_test.go: Defines the test cases and creates a test suite for running them. 

Runtime requirements:
Golang 1.24+

Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```