# 📘 Assignment: Testing C# Algorithms with xUnit

## 🎯 Objective

Practice writing and running automated tests for a small C# algorithm with xUnit. Check expected results as well as boundary and invalid-input behavior.

## 📝 Tasks

### 🛠️ Set Up xUnit and Test Typical Inputs

#### Description
Create an xUnit test project and implement a `NumberAnalyzer.FindMaximum(int[] numbers)` method that returns the largest value in an array.

#### Requirements
Completed program should:

- Create an xUnit test project with the .NET CLI.
- Define `FindMaximum(int[] numbers)` and write tests for arrays with positive values, all-negative values, and a single value.
- Verify each test with an expected maximum using xUnit assertions.

### 🛠️ Test Boundary and Invalid Inputs

#### Description
Extend the tests to cover arrays that do not contain a valid set of values, then update the method so its behavior is clear and consistent.

#### Requirements
Completed program should:

- Add a test confirming that an empty array causes `FindMaximum` to throw `ArgumentException`.
- Add a test confirming that a null array causes `FindMaximum` to throw `ArgumentNullException`.
- Run `dotnet test` and confirm all typical-input, boundary, and invalid-input tests pass.