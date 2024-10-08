# Conditionals and Loops in Python

When writing a Python script, the code typically executes sequentially. However, control flow structures such as conditionals and loops allow for more dynamic behavior by breaking this sequential flow. These structures can create branches in the code or repeat specific sections until certain conditions are met.

## Conditional Statements

Conditional statements allow the script to branch into different paths based on specific conditions, making the code more flexible and reusable.

- **If-then-else Statements**: The `if` statement uses relational operators to test an expression. If the condition evaluates to `True`, the code block following the colon (`:`) is executed. If `False`, the `else` block is executed.
  
- **Elif Statements**: The `elif` (else if) keyword allows for multiple conditions to be tested in sequence after the initial `if` statement. This creates multiple branches for code execution.

## Iterating Code with While Loops

While loops allow a block of code to be executed repeatedly as long as a specified condition remains `True`.

- The `while` statement tests an expression using relational operators. If the condition evaluates to `True`, the loop executes its code block and returns to the top to test the condition again. If `False`, the loop ends and the program moves to the next section of code.

- **Infinite Loops**: Care should be taken to ensure that loops are given a stopping condition. Otherwise, you risk creating an **infinite loop** where the code continues to execute indefinitely.

## Iterating Code with For Loops

For loops require an **iterable object** (such as a list, tuple, or range). The loop executes a block of code for each value within the iterable object.

- Once all the values have been processed, the loop finishes, and the program moves on to the next part of the code.

## Conditional and Loop Control

Control structures can be fine-tuned or interrupted early by specific control keywords:

- **Break**: Exits a loop early, skipping any remaining iterations, and moves to the next section of the code.
  
- **Continue**: Skips the current iteration and moves directly to the next iteration of the loop.
  
- **Else (with Loops)**: The `else` block can be used with loops and will be executed once the loop completes all its iterations unless a `break` statement is encountered.
  
- **Pass**: Does nothing. It is a placeholder that is syntactically required but does not result in any operation.

