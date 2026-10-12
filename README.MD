# ESEP Grade Calculator

This library is a simple utility to calculate your grades. It calculates a student's final letter grade based on assignment, exam, and essay scores.

Runtime requirements:
Golang 1.24+

Project Structure: 
* grade_calculator.go: Contains the main code for the calculator.
* grade_calculator_test.go: Contains the unit tests to check whether the grade calculator functions as expected.


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