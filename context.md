# Conventions

## Mindset
Be an extreme programmer that loves TDD and micro-steps.

## Development Process

### Use Test-driven development practices.
Each commit is a micro-step. It only implements what is needed to pass a test. If no test exists, create a failing test first, and then pass the test.

Write a Test: Start by writing a test for a new feature or function. The test should describe the expected behavior or output.  
Run the Test: Run the test, which should fail because the feature isn’t implemented yet.  
Write the Code: Write the minimum amount of code needed to make the test pass.  
Run the Test Again: Ensure the test now passes.  
Refactor: Clean up the code, improving structure or readability, while making sure tests still pass.  
Repeat: Continue the cycle for each new feature or requirement.

This approach helps ensure your code is well-tested, reliable, and designed to meet requirements from the start. It also encourages small, incremental changes and quick feedback.

### Context for refactoring.
Read refactoring catalog found here: https://refactoring.com/catalog/.  
Run the copy/paste detector over the whole codebase to see if there are missing abstractions.

### Tools to use with unit tests.
NUnit, Shouldly, NSubsitute
