# Problem Solving

Problem solving is the process of identifying a problem, developing an algorithm for the identified problem, and finally implementing the algorithm to develop a computer program.

## Steps of Problem Solving

1. Analyzing a problem
2. Developing an algorithm
3. Coding
4. Testing and debugging

---

## 1. Analyzing a Problem

It is important to clearly understand a problem before we begin to find a solution for it.

The principal components of analyzing a problem are:

- Decide the core functionality that our solution should have.
- Figure out the input to be accepted.
- Determine the output to be produced.

---

## 2. Developing an Algorithm

It is important to design a solution before writing program code for a given problem.

An algorithm is a finite sequence of well-defined steps used to solve a problem and obtain the desired result or output.

There can be more than one algorithm possible for a problem. We need to select the most suitable one based on factors such as efficiency and simplicity.

### Characteristics of a Good Algorithm

- **Precision:** The steps are precisely stated or defined.
- **Uniqueness:** The result of each step is clearly defined and depends on the input and the result of the previous step.
- **Finiteness:** The algorithm always stops after a finite number of steps.
- **Input:** The algorithm may receive one or more inputs.
- **Output:** The algorithm produces one or more outputs.

---

## 3. Representation of an Algorithm

There are two common ways to represent an algorithm:

### Flowchart

A flowchart is a visual representation of an algorithm using graphical symbols and diagrams. Each shape represents a step or operation in the solution process.

### Pseudocode

Pseudocode is another way to represent an algorithm. It is a non-formal, human-readable description of the instructions that a computer must follow in a particular order.

Pseudocode cannot be executed directly by a computer, and there is no single standard for writing it.

### Common Keywords Used in Pseudocode

- Input
- Output
- Print
- Compute
- If
- Else
- While
- True
- False
- Increment
- Decrement

### Benefits of Pseudocode

- It helps us write the solution in a human-readable form before coding.
- It helps prevent important steps from being left out.
- It allows non-programmers to review and understand the steps of a solution.

---

## 4. Flow of Control

Flow of control shows the order in which events or statements are executed in an algorithm or program.

The flow of control can be:

- **Sequence:** All the steps are executed one after another.
- **Selection:** A set of statements is selected for execution based on a condition.
- **Repetition:** A set of statements is repeatedly executed until a condition is satisfied. It is also called looping or iteration.

### Selection Statements

Selection statements are used when the execution of statements depends on a condition.

A condition produces a Boolean value: **True or False**.

#### If Statement

A set of statements is executed if the given condition is true. It is called a simple `if` or one-way branching statement.

Example:
- Find the biggest of two numbers using a simple `if` statement.

#### If-Else Statement

One set of statements is executed if the condition is true, and another set of statements is executed if the condition is false. It is called a two-way branching statement.

Example:
- Check whether a given number is even or odd.

#### If-Elif-Else Statement

The `if-elif-else` statement, also called an if ladder, is used when more than one condition has to be checked to select a statement or set of statements for execution.

Example:
- Find the largest of three numbers.

### Repetition Statements

A group of statements is executed repeatedly until a condition is satisfied.

The two common types of iteration in Python are:

- `for` loop
- `while` loop

Example:
- Find the sum and average of five numbers using a loop.

### Break and Continue

- **break:** Terminates the loop immediately.
- **continue:** Skips the remaining statements in the current iteration and moves to the next iteration.

### Nested Loops

A loop inside another loop is called a nested loop. Nested loops are commonly used for problems involving rows and columns and for creating pattern programs.

---

## 5. Verification of an Algorithm

When we have written an algorithm, we need to verify that it is working as expected.

The method of taking an input and running through the steps of the algorithm manually is called a **dry run**.

A dry run helps us to:

- Identify an incorrect step.
- Find a missing detail.
- Check whether the expected output is obtained.
- Improve or correct the algorithm.

It is important to test different types of input values, including possible boundary or special cases, so that the solution works correctly for a wide range of inputs.

---

## 6. Comparison of Algorithms

Algorithms can be compared based on the amount of processing time and memory they require.

These are commonly described using:

- **Time complexity:** The amount of time or number of operations required by an algorithm as the input size increases.
- **Space complexity:** The amount of memory required by an algorithm as the input size increases.

An algorithm can be selected based on how efficiently it uses processing time and memory.

---

## 7. Coding

Once the algorithm is finalized, it should be coded using a programming language.

Coding is the process of converting an algorithm into a computer program using a programming language.

The ordered set of instructions is written according to the syntax of the programming language.

### Syntax

Syntax is the set of rules or grammar that governs the formation of statements in a programming language, such as the spelling, order of words, and punctuation.

Machine-level languages consist of binary instructions represented using zeros and ones.

Low-level languages are closer to the machine and are generally more difficult for humans to understand and work with. This led to the development of high-level languages, which are closer to natural language and easier to read, write, and maintain.

Examples of high-level programming languages include:

- Fortran
- COBOL
- C
- C++
- Java
- Python

A program written in a high-level programming language is called **source code**.

The source code needs to be translated into a form that the computer can execute. This can be done using a compiler or an interpreter, depending on the language and implementation.

- **Compiler:** Generally translates the source code into another form before execution.
- **Interpreter:** Generally executes the source code by processing it during execution.

---

## 8. Testing and Debugging

**Testing** is the process of checking the correctness of a program by running it with different test data and checking whether the expected output is produced.

**Debugging** is the process of finding and correcting errors or bugs in a program.

### Types of Errors

#### Syntax Error

A syntax error occurs when the rules or grammar of the programming language are not followed.

#### Semantic or Logical Error

A logical error occurs when the program runs but produces an incorrect result because the program logic is wrong.

#### Runtime Error

A runtime error occurs while the program is being executed.

---

## 9. Decomposition

Decomposition is the process of breaking down a complex problem or program into smaller and more manageable subproblems.

Each subproblem can be examined and solved separately. This helps reduce complexity and makes the solution easier to understand, develop, test, and maintain.

Different subproblems can also be assigned to people or teams with relevant expertise. After solving and testing the individual subproblems, they can be integrated to form the complete solution.
