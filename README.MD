# ESEP Grade Calculator

The ESEP Grade Calculator is a small Go library for managing and calculating course grades. It supports multiple grade types (Assignments, Exams, and Essays), applies weighted averages, and converts numeric scores into final letter grades (A–F).

Runtime requirements:
Golang 1.24+

📦 Features

Add assignments, exams, and essays with numeric scores

Weighted grade calculation (50% assignments, 35% exams, 15% essays)

Automatic conversion from numeric average to letter grade (A–F)

Unit tests to verify grade logic

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