# ![CodeRed Logo](https://res.cloudinary.com/dm23rhuct/image/upload/v1729399068/nul6rfquxd0nymrcwcey.jpg) **CodeRed Chapter 1: Basic C Programming**


# Lecture 1: Introduction to C Programming
### By : Shivam Mishra and Naman Yadav


# 1. Introduction and Algorithms

## Introduction
- **Algorithm**: A step-by-step procedure to solve a problem.
  - **Definition**: A finite sequence of well-defined instructions, typically to solve a class of problems or perform a computation.
  - **Purpose**: To provide a clear set of instructions for solving a problem or performing a task.

- **Characteristics of Algorithms**:
  - **Finite**: Must terminate after a finite number of steps.
    - **Explanation**: An algorithm must have a clear stopping point; it cannot run indefinitely.
  - **Definite**: Each step must be precisely defined.
    - **Explanation**: The instructions should be unambiguous and clear.
  - **Input**: Zero or more inputs are externally supplied.
    - **Explanation**: An algorithm can have no inputs or multiple inputs to process.
  - **Output**: At least one output is produced.
    - **Explanation**: An algorithm must produce at least one result.
  - **Effective**: All operations must be basic enough to be performed exactly and in a finite amount of time.
    - **Explanation**: Each step should be simple enough to be executed without any ambiguity.

## Example of an Algorithm
1. **Start**: Begin the algorithm.
2. **Input two numbers, A and B**: Receive two numbers from the user or another source.
3. **Add A and B and store the result in Sum**: Perform the addition operation and store the result.
4. **Output Sum**: Display or return the result of the addition.
5. **End**: Terminate the algorithm.

# 2. Flow Charts

## Introduction
- **Flowchart**: A graphical representation of an algorithm.
  - **Purpose**: To visualize the sequence of steps in an algorithm, making it easier to understand and communicate.

- **Symbols**:
  - **Oval**: Start/End
    - **Usage**: Indicates the beginning and end of the flowchart.
  - **Parallelogram**: Input/Output
    - **Usage**: Represents input and output operations.
  - **Rectangle**: Process
    - **Usage**: Denotes a process or operation to be performed.
  - **Diamond**: Decision
    - **Usage**: Indicates a decision point, typically a yes/no question or true/false condition.
  - **Arrow**: Flow of control
    - **Usage**: Shows the direction of the flow of control from one step to another.

## Example of a Flowchart
1. **Start**: Oval
   - **Description**: Marks the beginning of the flowchart.
2. **Input A, B**: Parallelogram
   - **Description**: Represents the input operation where two numbers, A and B, are received.
3. **Process (Sum = A + B)**: Rectangle
   - **Description**: Denotes the process of adding A and B and storing the result in Sum.
4. **Output Sum**: Parallelogram
   - **Description**: Represents the output operation where the result Sum is displayed.
5. **End**: Oval
   - **Description**: Marks the end of the flowchart.

# 3. Intro to C, Characteristics

## Introduction to C
- **C Language**: A general-purpose, procedural programming language.
  - **History**: Developed by Dennis Ritchie at Bell Labs in the early 1970s.
  - **Purpose**: Designed for system programming, developing operating systems, and embedded systems.
  - **Influence**: Influenced many later languages such as C++, Java, and C#.

## Characteristics of C
- **Simple**: Easy to learn and use.
  - **Explanation**: The syntax is straightforward, making it accessible for beginners.
- **Structured**: Supports structured programming.
  - **Explanation**: Encourages the use of functions and control structures for better code organization.
- **Portable**: Code can be run on different machines with little or no modification.
  - **Explanation**: Programs written in C can be compiled and executed on various hardware platforms.
- **Efficient**: Provides low-level access to memory and minimal runtime support.
  - **Explanation**: Allows for fine-tuned performance and efficient use of resources.
- **Rich Library**: Comes with a rich set of built-in functions.
  - **Explanation**: Provides a wide range of standard library functions for various tasks.

# 4. Constants, Data Types, Variables, Keywords, Input/Output Statements

## Constants
- **Definition**: Fixed values that do not change during the execution of a program.
  - **Purpose**: Used to represent values that remain constant throughout the program.

- **Types**:
  - **Integer Constants**: e.g., 10, -5
    - **Explanation**: Whole numbers without a fractional part.
  - **Floating-point Constants**: e.g., 3.14, -0.001
    - **Explanation**: Numbers with a fractional part.
  - **Character Constants**: e.g., 'a', '1'
    - **Explanation**: Single characters enclosed in single quotes.
  - **String Constants**: e.g., "Hello"
    - **Explanation**: Sequence of characters enclosed in double quotes.

## Data Types
- **Basic Data Types**:
  - **int**: Integer
    - **Explanation**: Used to store whole numbers.
  - **float**: Floating-point number
    - **Explanation**: Used to store numbers with a fractional part.
  - **char**: Character
    - **Explanation**: Used to store single characters.
  - **double**: Double-precision floating-point number
    - **Explanation**: Used to store large floating-point numbers with double precision.

## Variables
- **Definition**: Named storage locations in memory.
  - **Purpose**: Used to store data that can be modified during program execution.

- **Declaration**: `data_type variable_name;`
  - **Explanation**: Specifies the type of data the variable will hold and its name.
  - **Example**: `int age;`
    - **Explanation**: Declares a variable named `age` of type `int`.

## Keywords
- **Definition**: Reserved words with special meaning in C.
  - **Purpose**: Used to perform specific operations and cannot be used as identifiers.

- **Examples**: `int`, `return`, `if`, `else`, `while`, `for`
  - **Explanation**: Each keyword has a predefined meaning and function in the language.

## Input/Output Statements
- **Input**: `scanf` function
  - **Syntax**: `scanf("format_specifier", &variable);`
    - **Explanation**: Reads input from the standard input (keyboard) and stores it in the specified variable.
  - **Example**: `scanf("%d", &age);`
    - **Explanation**: Reads an integer from the user and stores it in the variable `age`.

- **Output**: `printf` function
  - **Syntax**: `printf("format_specifier", variable);`
    - **Explanation**: Prints output to the standard output (screen).
  - **Example**: `printf("Age: %d", age);`
    - **Explanation**: Prints the value of the variable `age` with the label "Age:".