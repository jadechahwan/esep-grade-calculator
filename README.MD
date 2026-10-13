# ESEP Grade Calculator

This is a simple Go project that calculates a final letter grade based on assignments, exams, and essays.

## Requirements
Go 1.24.4 or newer

## How It Works
The calculator uses these weights:
Assignments: 50%
Exams: 35%
Essays: 15%

It calculates the average for each category and uses the weights to get the final grade.

Letter grades:
A: 90 or higher
B: 80-89
C: 70-79
D: 60-69
F: Below 60

## Project Files
`grade_calculator.go` - Main code for calculating grades.
`grade_calculator_test.go` - Unit tests for the calculator.
`go.mod` - Go module information.

## Running Tests
From the main project folder, run:

```bash
cd grade_calculator/
go test ./...
```

## Checking Code Coverage
To check code coverage, run:

```bash
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```