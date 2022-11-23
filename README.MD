## Usage

Ton install, run `npm i`.

To run the tests, run `npm run watch`.

## Workflow of TDD

1. Write a failing test. Stop writing the test as soon as it fails.
2. Write the minimal production code required for the test to pass. Stop writing any code once the test passes.
3. Refactor the test code and the production code without altering the functionality. All tests should pass.

## Greeter Kata

#### Before you start:

- **Try not to read ahead.**
- **Do one task at a time. The trick is to learn to work incrementally.**

All tests should always pass, regardless of environment conditions.

#### The task:

Implement a STACK data structure without using a JS array. Where the LAST item IN is the FIRST item out.

1. Should have a property `top` that represents the index of the item at the top of the stack. When it's empty it should have a value of -1. Should have a property `items` where the data is stored.
2. Should have a method `push` that puts a value on top of the stack.
3. Should have a method `pop` that removes a value from the top of the stack.
