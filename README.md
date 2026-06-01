# Function Calling Another Function in C

## Overview

This project demonstrates how functions can call other functions in C.

The program uses two user-defined functions:

* `myFunction()`
* `myOtherFunction()`

When `myFunction()` is executed, it prints a message and then calls `myOtherFunction()`, which prints another message.

---

## Concepts Covered

* Function declaration (prototype)
* Function definition
* Function calling
* Nested function calls
* Program execution flow

---

## Project Description

The program begins execution from the `main()` function.

### Execution Flow

1. `main()` calls `myFunction()`
2. `myFunction()` displays a message
3. `myFunction()` calls `myOtherFunction()`
4. `myOtherFunction()` displays another message
5. Program execution ends

This example shows how functions can interact with each other to create modular and organized programs.

---

## Key Concepts Used

### Function Prototypes

```text id="a2v8kx"
void myFunction();
void myOtherFunction();
```

Function prototypes inform the compiler about functions before they are used.

### Function Call

```text id="m4q9dt"
myFunction();
```

Starts the execution of the user-defined function.

### Nested Function Call

```text id="n7j3pw"
myOtherFunction();
```

A function calling another function.

---

## Sample Output

```text id="u6f2ly"
Some text in myFunction
Hey! Some text in myOtherFunction
```

---

## Learning Outcomes

* Understanding function declarations and definitions
* Learning how functions communicate with each other
* Understanding program execution flow
* Writing modular and reusable code

---

## Real-World Applications

Function-to-function calls are commonly used in:

* Embedded systems
* Operating systems
* Web applications
* Game development
* Large-scale software projects

They help break complex tasks into smaller, manageable modules.

---

## Author

Amrutha D N
