# CodeGoPython : Understanding How Programming Languages Run

Welcome to your introduction to programming with Python! This repository contains beginner-friendly tutorials, focusing on how code gets executed on your computer.

CodeGoPython is a starter platform designed to help you understand the intricacies of programming languages, specifically Python.
It provides a structured learning experience that covers the fundamentals of the language, including syntax, data types, control structures, and more.

**But actually, CodeGo is Fit!**

## Contents <!-- omit from toc -->

[ [Top](#codegopython--understanding-how-programming-languages-run) ]

- [CodeGoPython : Understanding How Programming Languages Run](#codegopython--understanding-how-programming-languages-run)
  - [Getting Started](#getting-started)
  - [What's in This Repository](#whats-in-this-repository)
    - [Python Directory (`/python/`)](#python-directory-python)
  - [Learning Path](#learning-path)
  - [Key Takeaways](#key-takeaways)
  - [What is Code Interpretation vs Compilation?](#what-is-code-interpretation-vs-compilation)
    - [Compiled Languages (Traditional Java)](#compiled-languages-traditional-java)
    - [Interpreted Languages (Python)](#interpreted-languages-python)
  - [Why This Matters for Beginners](#why-this-matters-for-beginners)
    - [Learning with Interpreters](#learning-with-interpreters)
  - [The Big Picture](#the-big-picture)

## Getting Started

[ [Top](#codegopython--understanding-how-programming-languages-run) ]

To get started, clone this repository to your local machine:

```bash
cd ~/Projects
git clone https://github.com/ZipCodeCore/CodeGoPython
```

Then, navigate to the repository:

```bash
cd CodeGoPython
# and then,
cd python
```

Use a browser to be able to see the markdown files.
JavaSmall.md or PythonSmall.md will be where you start!!

## What's in This Repository

[ [Top](#codegopython--understanding-how-programming-languages-run) ]

This repository contains a tutorial for python:

### Python Directory (`/python/`)

[ [Top](#codegopython--understanding-how-programming-languages-run) | [Back](#whats-in-this-repository) ]

- **[README.md](python/README.md)**: Getting started with Python interpreter
- **[PythonSmall.md](python/PythonSmall.md)**: Interactive Python programming
- **[VARS.md](python/VARS.md)**: Understanding Python variables
- **[ClassPerson.md](python/ClassPerson.md)**: Creating Python classes

## Learning Path

[ [Top](#codegopython--understanding-how-programming-languages-run) ]

1. **Start with Python** - this repository focuses on Python programming
2. **Use the interpreter** - python3 for Python
3. **Type, don't copy-paste** - build muscle memory and understanding
4. **Experiment beyond the examples** - interpreters make this safe and fun

## Key Takeaways

[ [Top](#codegopython--understanding-how-programming-languages-run) ]

- **Interpreters** let you run code immediately, line by line
- **Python** has always been interpreted, making it beginner-friendly

## What is Code Interpretation vs Compilation?

[ [Top](#codegopython--understanding-how-programming-languages-run) ]

When you write code, your computer doesn't understand it directly. Programming languages need to be translated into machine language (1s and 0s) that your computer can execute. There are two main ways this happens:

### Compiled Languages (Traditional Java)

[ [Top](#codegopython--understanding-how-programming-languages-run) | [Back](#what-is-code-interpretation-vs-compilation) ]

**Compilation** is like translating an entire book before anyone can read it:

- You write your Java code in a `.java` file
- A **compiler** (like `javac`) translates your entire program into bytecode
- The Java Virtual Machine (JVM) then runs this compiled bytecode
- If there are errors anywhere in your code, the compiler catches them before anything runs
- You must fix all errors before your program can run

**Example workflow:**

```
Write code → Compile (javac) → Run (java) → See results
    ↓              ↓             ↓
hello.java → hello.class → Output
```

### Interpreted Languages (Python)

[ [Top](#codegopython--understanding-how-programming-languages-run) | [Back](#what-is-code-interpretation-vs-compilation) ]

**Interpretation** is like having a live translator who translates as you speak:

- You write Python code and run it immediately
- The **interpreter** reads your code line by line and executes it instantly
- Errors are found and reported as the program runs, not before
- You can test small pieces of code quickly without compiling

**Example workflow:**

```
Write code → Run directly → See results immediately
    ↓             ↓
hello.py → Output (no compilation step)
```

## Why This Matters for Beginners

[ [Top](#codegopython--understanding-how-programming-languages-run) ]

### Learning with Interpreters

[ [Top](#codegopython--understanding-how-programming-languages-run) | [Back](#why-this-matters-for-beginners) ]

- **Immediate feedback**: See results instantly
- **Experiment freely**: Try code snippets without writing full programs
- **Learn incrementally**: Build understanding one concept at a time
- **Quick debugging**: Test small pieces to understand what went wrong

## The Big Picture

[ [Top](#codegopython--understanding-how-programming-languages-run) ]

Understanding how your code runs helps you become a better programmer. Interpreters are great for learning and quick experiments. Compilers help you build robust, efficient programs. Modern development often uses both approaches - interpreters for testing ideas, compilers for building final applications.

Ready to start? `cd python` and begin your programming journey!

[ [Top](#codegopython--understanding-how-programming-languages-run) | [Next](python/README.md) ]
