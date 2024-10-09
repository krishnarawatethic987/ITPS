# Problem Solving Phases

## Problem Definition
- A problem is an unpleasant condition that needs to be corrected.
- Examples include algebra equations or being caught in the rain without an umbrella.

## Importance of Problem Solving
- Helps identify opportunities and exert control over the future.
- Involves defining, determining the cause, identifying solutions, and implementing them.

## Phases of Problem Solving

### 1. Understanding the Problem
- Carefully read the problem.
- Identify required outputs and inputs.
- Ensure the relationship between input and output is clear.

### 2. Making a Plan of Solution
- Delay evaluating alternatives at first.
- Brainstorm and include everyone in generating ideas.
- Specify short- and long-term alternatives.

### 3. Carrying Out the Plan
- Identify constraints of the ideal solution.
- Eliminate solutions that don't meet these constraints.
- Assess risks and choose the best solution.

### 4. Implementing the Solution
- Plan and prepare for implementation.
- Take action and monitor its effects.
- Review the success of the action.

### 5. Looking Back (Verification)
- Evaluate the outcome of the solution.
- Check if the solution answered the initial questions.
- Reflect on the effectiveness of the process.

# Flowcharts

## What is a Flowchart?
- A flowchart is a graphical representation of steps in a process or algorithm.
- It uses shapes like boxes and arrows to illustrate the flow of the process.

## Uses of a Flowchart
- Identify bottlenecks and defects in processes.
- Communicate and visualize complex workflows.
- Useful in explaining algorithms to non-technical people.

## Common Flowchart Symbols

1. **Oval (Terminator)**: Represents the start or end of the process.
2. **Rectangle (Process)**: Shows a step or action in the process.
3. **Diamond (Decision)**: Represents a decision point with Yes/No options.
4. **Parallelogram (Data Input/Output)**: Indicates input to or output from a process.
5. **Circle (Connector)**: Connects different parts of the flowchart or links to another process.
6. **Document**: Represents a document or report in the flow.
7. **Stored Data**: Shows data stored in memory or other storage devices.
8. **Manual Input**: Indicates data that must be manually entered by the user.
9. **Subroutine (Predefined Process)**: Represents a reusable process or subroutine.

## Steps to Draw a Flowchart

![Alt Text](https://wcs.smartdraw.com/flowchart/img/basic-symbols-table.jpg?bn=15100111938)

1. Layout each step of your process with a shape.
2. Connect the shapes using arrows to show the sequence.
3. Organize and emphasize key steps with colors or design elements.

## Best Practices
- Use clear and consistent symbols.
- Label arrows and decision points to avoid confusion.
- Break down complex processes into smaller sub-processes when necessary.

# Algorithms

## What is an Algorithm?
- An algorithm is a step-by-step process to achieve a specific outcome.
- It is used to solve problems efficiently by using minimal time and memory.

## Designing an Algorithm
To design an algorithm, you need:
1. **Problem definition**: What needs to be solved.
2. **Constraints**: Conditions that must be met.
3. **Input**: Data required for the solution.
4. **Output**: Expected result.
5. **Solution steps**: The method to solve the problem.

## Example Algorithm (Sum of Three Numbers)
1. **START**
2. Declare variables for three numbers.
3. Input the numbers.
4. Compute their sum.
5. Print the sum.
6. **END**

## Performance Analysis of Algorithms
Factors to consider:
1. **Space Complexity**: Memory required.
2. **Time Complexity**: Time taken to execute.

## Types of Algorithms
1. **Recursive**
2. **Dynamic programming**
3. **Backtracking**
4. **Divide and conquer**
5. **Greedy**
6. **Brute Force**
7. **Randomized**

## Common Uses
- Algorithms are used in daily tasks like search engines, video players, scheduling, and data sorting.

# Features, Applications, and Structure of C Programming

## Features of C Language

1. **Simple and Efficient**: Easy to understand and allows direct hardware manipulation.
2. **Speed**: Compiler-based, faster than languages like Java or Python.
3. **Modularity**: Code can be stored in libraries for reuse.
4. **Portability**: Code can run on different systems without modification.
5. **Library Support**: Rich set of built-in and user-defined functions.
6. **Dynamic Memory Allocation**: Allows memory to be managed efficiently.
7. **Case Sensitive**: Differentiates between uppercase and lowercase letters.

## Applications of C Language

1. **Operating Systems**: Used to develop Unix, Windows, and Android OS.
2. **Embedded Systems**: Ideal for hardware programming.
3. **Graphical User Interfaces (GUIs)**: Tools like Adobe Photoshop were built using C.
4. **New Programming Platforms**: Basis for languages like C++ and MATLAB.
5. **Databases**: MySQL and similar systems are written in C/C++.
6. **Game Development**: Used for high-speed games and animations.
7. **Compiler Design**: Many programming language compilers are built using C.

## Structure of a C Program

1. **Header Files Inclusion**: Include files like `#include <stdio.h>` for function declarations.
2. **Main Function Declaration**: `int main()` is where the program execution begins.
3. **Variable Declaration**: Declare variables before using them.
4. **Body**: Contains the operations or logic of the program.
5. **Return Statement**: Ends the main function, often with `return 0;`.

# Input and Output Functions in C

## Types of I/O Functions in C

### 1. Unformatted I/O Functions
- Works only with character data.
- **Functions**:
  - `getch()`: Reads a character without echoing it.
  - `getche()`: Reads a character and displays it.
  - `getchar()`: Reads a character and displays it after pressing Enter.
  - `gets()`: Reads a string from the user.

### 2. Formatted I/O Functions
- Uses format specifiers to format input/output.
- **Functions**:
  - `scanf()`: Reads formatted input.
  - `printf()`: Prints formatted output.
  - `sscanf()`: Reads data from a string.
  - `sprintf()`: Stores formatted data into a string.

## Common Format Specifiers
- `%d`: Integer
- `%u`: Unsigned integer
- `%ld`: Long integer
- `%f`: Float
- `%lf`: Double
- `%s`: String

## Importance of Indentation
- Makes code easier to read and understand.
- Improves the program's readability and maintainability.

## Difference between `getch()`, `getche()`, and `getchar()`
- `getch()`: Does not display the character and does not wait for Enter.
- `getche()`: Displays the character without waiting for Enter.
- `getchar()`: Displays the character and waits for Enter.

# Data Types and Variables in C

## Data Types in C

1. **Primary Data Types**: Predefined types like `int`, `char`, `float`, and `double`.
2. **Derived Data Types**: Created from primary types (e.g., arrays).
3. **User-defined Data Types**: Defined by the user using `typedef` (e.g., `typedef int integer`).

## Memory Space and Format Specifiers

- `char`: 1 byte, `%c`
- `int`: 2 bytes, `%d`
- `long`: 4 bytes, `%ld`
- `float`: 4 bytes, `%f`
- `double`: 8 bytes, `%lf`

## Constants

- Defined using:
  - `const` keyword (e.g., `const int num = 5;`)
  - `#define` (e.g., `#define PI 3.14`)
- **Types of constants**: Integer, Floating-point, Character, String.

## Variables

- Quantities whose values can change during program execution.
- **Local Variables**: Declared inside a function, accessible only within that function.
- **Global Variables**: Declared outside functions, accessible throughout the program.

## Rules for Naming Variables

1. Cannot start with a digit.
2. No special characters allowed except the underscore (`_`).
3. Keywords cannot be used as variable names.

# Operators in C

## Types of Operators in C

1. **Arithmetic Operators**: `+`, `-`, `*`, `/`, `%`
   - Used for basic mathematical operations.

2. **Relational Operators**: `>`, `<`, `>=`, `<=`, `==`, `!=`
   - Used to compare values, returning true (1) or false (0).

3. **Logical Operators**: `&&` (AND), `||` (OR), `!` (NOT)
   - Combines multiple conditions or inverts a condition.

4. **Assignment Operators**: `=`, `+=`, `-=`, `*=`, `/=`, `%=`
   - Used to assign values to variables.

5. **Increment and Decrement Operators**: `++`, `--`
   - Increase or decrease a variable's value by 1.

6. **Conditional (Ternary) Operator**: `? :`
   - Short form of the if-else statement.

7. **Miscellaneous Operators**: `sizeof`, `,` (comma operator)
   - `sizeof` gives the size of a data type; the comma operator separates expressions.

8. **Bitwise Operators**: Works directly on bits, using symbols like `&`, `|`, `^`, `~`, `<<`, `>>`.

# Bitwise Operators in C

## Types of Bitwise Operators

1. **Bitwise AND (`&`)**: Both bits must be 1 to get 1.
2. **Bitwise OR (`|`)**: At least one bit must be 1 to get 1.
3. **Bitwise XOR (`^`)**: Results in 1 if bits are different.
4. **Bitwise NOT (`~`)**: Flips bits (1 becomes 0, and 0 becomes 1).
5. **Left Shift (`<<`)**: Shifts bits to the left, adding zeros.
6. **Right Shift (`>>`)**: Shifts bits to the right, discarding the rightmost bits.

## Key Points

- **AND (`&`)**: Used for masking bits.
- **OR (`|`)**: Used for setting specific bits.
- **XOR (`^`)**: Used to toggle bits.
- **NOT (`~`)**: Computes the 2's complement, changing the sign.
- **Shift Operators**: Efficient way to multiply or divide by powers of 2.

# Expressions in C

## Expression
- An expression is a combination of operators and operands that evaluates to a single value.
- **Example**: `10 + 15` evaluates to `25`.

## Operator Precedence and Associativity

- **Precedence**: Determines which operator is evaluated first.
  - Higher precedence operators are evaluated before lower ones.
  - **Example**: `10 + 20 * 30` is evaluated as `10 + (20 * 30)`.

- **Associativity**: Determines the order of evaluation for operators of the same precedence.
  - **Left-to-right**: Most arithmetic operators (`+`, `-`, `*`, `/`).
  - **Right-to-left**: Assignment and unary operators.

## Types of Expressions

1. **Arithmetic Expressions**: Uses arithmetic operators (`+`, `-`, `*`, `/`).
2. **Relational Expressions**: Uses relational operators (`==`, `!=`, `<`, `>`).
3. **Logical Expressions**: Uses logical operators (`&&`, `||`, `!`).
4. **Assignment Expressions**: Involves the assignment operator (`=`).
5. **Mixed Mode Expressions**: Combines integers and floating-point numbers.

# Decision Control Statements in C

## Purpose
- To execute code based on conditions, allowing selective execution of statements.

## Types of Decision Statements

1. **if Statement**: Executes code block if the condition is true.
   - **Syntax**:
     ```c
     if (condition) {
         // statements
     }
     ```

2. **if-else Statement**: Executes one block if the condition is true, otherwise executes another.
   - **Syntax**:
     ```c
     if (condition) {
         // statements if true
     } else {
         // statements if false
     }
     ```

3. **Nested if Statement**: An `if` statement inside another `if` statement.
   - Used for multiple conditions.

4. **if-else-if Ladder**: Tests multiple conditions in sequence.
   - Executes the first true condition and ignores the rest.

# Switch Statement in C

## Purpose
- Used to execute one code block among many options based on the value of an expression.

## Syntax
```c
switch(expression) {
    case value1:
        // statements
        break;
    case value2:
        // statements
        break;
    default:
        // default statements
}
```

## Key Points

1. **Break Statement**: Stops the execution from falling into the next case.
2. **Default Case**: Optional; executes if no matching case is found.
3. **Case Values**: Must be constant and unique.
4. **Nesting**: Possible but not recommended as it reduces code readability.
5. **Character Cases**: Switch cases can use characters like `case 'A':`.

## Common Use Cases
- Menu-driven programs
- Calculators
- Checking conditions like even/odd numbers or vowels/consonants


# Conditional Operator and goto Statement in C

## Conditional Operator (?:)

### Purpose
- A shorthand for the if-else statement, also known as the ternary operator.

### Syntax
```c
condition ? expression1 : expression2;
```

### How it works
- If the condition is true, `expression1` is executed.
- If the condition is false, `expression2` is executed.

### Use cases
- Finding maximum values
- Checking conditions in a compact form

## goto Statement

### Purpose
- Alters the normal sequence of execution by jumping to a specific label.

### Syntax
```c
goto label;
...
label:
    // statements
```

### Key Points
- Can jump both forward and backward in code.
- Useful in specific scenarios like exiting nested loops or repetitive tasks but can make code harder to follow.

## Best Practices

- **Conditional Operator**:
  - Best for simple, concise if-else scenarios.

- **goto Statement**:
  - Use sparingly to avoid complex, hard-to-read code.
