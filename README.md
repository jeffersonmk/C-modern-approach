# C Programming: A Modern Approach

My solutions and implementations for the exercises and programming projects from **C Programming: A Modern Approach, 2nd Edition**, by **K. N. King**.

This repository is part of my journey to learn and practice the C programming language through the exercises and programming projects presented throughout the book.

The goal is not only to complete the problems, but also to understand the concepts behind them, improve problem-solving skills, and gradually develop better C programming practices.

---

## About the Book

**C Programming: A Modern Approach** by K. N. King is a comprehensive textbook designed to teach the C programming language from the fundamentals to more advanced topics.

The book follows a gradual learning approach. It begins with basic C syntax and programming concepts and progressively introduces more advanced subjects such as:

* Variables and data types
* Expressions and operators
* Selection and iteration statements
* Functions
* Arrays
* Program organization
* Pointers
* Strings
* Structures, unions, and enumerations
* Dynamic memory management
* Low-level programming
* The C standard library
* Input/output
* Error handling
* Advanced C features

The **second edition** also includes coverage of the C99 standard, additional exercises, and longer programming projects.

---

## Repository Structure

The repository is organized **chapter by chapter**.

Each chapter contains two main directories:

* `exercises/` — exercises designed to practice and reinforce individual concepts.
* `projects/` — larger programming problems that combine concepts learned throughout the chapter.

The basic structure is:

```text
C-Programming-A-Modern-Approach/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── Chapter-01/
│   ├── exercises/
│   └── projects/
│
├── Chapter-02/
│   ├── exercises/
│   └── projects/
│
├── Chapter-03/
│   ├── exercises/
│   └── projects/
│
├── Chapter-04/
│   ├── exercises/
│   └── projects/
│
├── ...
│
└── Chapter-27/
    ├── exercises/
    └── projects/
```

This structure keeps exercises and projects separated while making it easy to navigate through the book in the same order as the chapters.

---

## Exercises

The `exercises/` directory contains the exercises proposed in each chapter.

Exercises are generally smaller problems focused on a particular concept or programming technique.

For example:

```text
Chapter-02/
└── exercises/
    ├── Exercise-01/
    │   └── solution.c
    │
    ├── Exercise-02/
    │   └── solution.c
    │
    ├── Exercise-03/
    │   └── solution.c
    │
    └── ...
```

Each exercise can have its own directory.

This makes it possible to keep the source code, notes, alternative implementations, or additional files related to an exercise together.

### Example

```text
Chapter-04/
└── exercises/
    ├── Exercise-01/
    │   └── solution.c
    │
    ├── Exercise-02/
    │   ├── solution.c
    │   └── README.md
    │
    └── Exercise-03/
        └── solution.c
```

A `README.md` inside an exercise is optional and can be used when additional explanation is useful.

---

## Programming Projects

The `projects/` directory contains the **Programming Projects** proposed at the end of each chapter.

These problems are generally larger than regular exercises and are intended to encourage the application of several concepts together.

Each project receives its own directory:

```text
Chapter-02/
└── projects/
    ├── Project-01/
    │   └── solution.c
    │
    ├── Project-02/
    │   └── solution.c
    │
    ├── Project-03/
    │   └── solution.c
    │
    └── ...
```

For larger projects, additional files can be added when necessary:

```text
Project-01/
├── README.md
├── main.c
├── functions.c
└── functions.h
```

This allows the project structure to grow naturally when a problem requires multiple source files.

---

## Exercises vs. Projects

The distinction between the two directories is intentional.

### Exercises

Exercises are mainly used for:

* Practicing a specific concept
* Testing understanding
* Solving smaller programming problems
* Experimenting with C syntax
* Reinforcing concepts introduced in the chapter

```text
Chapter
└── exercises/
    ├── Exercise-01
    ├── Exercise-02
    ├── Exercise-03
    └── ...
```

### Programming Projects

Projects are intended to be more complete programming tasks.

They may require:

* Planning a solution
* Designing an algorithm
* Combining multiple concepts
* Writing more code
* Testing different cases
* Organizing the program
* Applying concepts from previous chapters

```text
Chapter
└── projects/
    ├── Project-01
    ├── Project-02
    ├── Project-03
    └── ...
```

In other words:

> **Exercises are focused practice. Projects are larger applications of what has been learned.**

---

## Chapter Organization

The repository follows the order of the book.

### Part I — Basic Features of C

```text
Chapter-01/
Chapter-02/
Chapter-03/
Chapter-04/
Chapter-05/
Chapter-06/
Chapter-07/
Chapter-08/
Chapter-09/
Chapter-10/
```

These chapters introduce the fundamental features of the C language and gradually build the foundation needed for writing C programs.

### Part II — Advanced Features of C

```text
Chapter-11/
Chapter-12/
Chapter-13/
Chapter-14/
Chapter-15/
Chapter-16/
Chapter-17/
```

These chapters introduce more advanced features, including pointers, strings, the preprocessor, larger program organization, structures, unions, enumerations, and advanced pointer usage.

### Part III — The C Standard Library

```text
Chapter-18/
Chapter-19/
Chapter-20/
Chapter-21/
Chapter-22/
Chapter-23/
Chapter-24/
Chapter-25/
Chapter-26/
Chapter-27/
```

These chapters focus on declarations, program design, low-level programming, and different parts of the C standard library.

---

## Naming Convention

A consistent naming convention is used throughout the repository.

### Chapters

```text
Chapter-01/
Chapter-02/
Chapter-03/
...
Chapter-27/
```

### Exercises

```text
Exercise-01/
Exercise-02/
Exercise-03/
...
```

### Projects

```text
Project-01/
Project-02/
Project-03/
...
```

### Source Files

For simple programs:

```text
solution.c
```

For larger projects:

```text
main.c
functions.c
functions.h
```

The structure can be adapted depending on the requirements of each problem.

---

## Example Complete Structure

A chapter containing both exercises and programming projects may look like this:

```text
Chapter-05/
│
├── exercises/
│   │
│   ├── Exercise-01/
│   │   └── solution.c
│   │
│   ├── Exercise-02/
│   │   └── solution.c
│   │
│   ├── Exercise-03/
│   │   ├── solution.c
│   │   └── README.md
│   │
│   └── Exercise-04/
│       └── solution.c
│
└── projects/
    │
    ├── Project-01/
    │   └── solution.c
    │
    ├── Project-02/
    │   ├── solution.c
    │   └── README.md
    │
    └── Project-03/
        ├── main.c
        ├── functions.c
        └── functions.h
```

This organization keeps the repository clean and makes it immediately clear whether a program is an exercise or a programming project.

---

## Compilation

The programs in this repository are written in C and can generally be compiled using GCC.

For a simple program:

```bash
gcc solution.c -o solution
```

Run it with:

```bash
./solution
```

For a stricter compilation:

```bash
gcc -Wall -Wextra -std=c11 -pedantic solution.c -o solution
```

Using compiler warnings is encouraged because they can help identify potential problems and improve code quality.

---

## Learning Approach

The repository follows a simple learning workflow:

```text
Read the chapter
      ↓
Study the examples
      ↓
Solve the exercises
      ↓
Work on the programming projects
      ↓
Review the solution
      ↓
Refactor and improve the code
```

The purpose is to avoid simply writing code that works.

The goal is to understand **why** the solution works and what could be improved.

When possible, solutions may be revisited later to improve:

* Readability
* Structure
* Naming
* Error handling
* Portability
* Efficiency
* Use of C language features

---

## Progress

The repository will be completed progressively as I work through the book.

| Chapter | Topic                                          | Exercises | Projects | Status        |
| ------- | ---------------------------------------------- | --------: | -------: | ------------- |
| 01      | Introducing C                                  |         — |        — | ⬜ Not started |
| 02      | C Fundamentals                                 |         — |        — | ⬜ Not started |
| 03      | Formatted Input/Output                         |         — |        — | ⬜ Not started |
| 04      | Expressions                                    |         — |        — | ⬜ Not started |
| 05      | Selection Statements                           |         — |        — | ⬜ Not started |
| 06      | Loops                                          |         — |        — | ⬜ Not started |
| 07      | Basic Types                                    |         — |        — | ⬜ Not started |
| 08      | Arrays                                         |         — |        — | ⬜ Not started |
| 09      | Functions                                      |         — |        — | ⬜ Not started |
| 10      | Program Organization                           |         — |        — | ⬜ Not started |
| 11      | Pointers                                       |         — |        — | ⬜ Not started |
| 12      | Pointers and Arrays                            |         — |        — | ⬜ Not started |
| 13      | Strings                                        |         — |        — | ⬜ Not started |
| 14      | The Preprocessor                               |         — |        — | ⬜ Not started |
| 15      | Writing Large Programs                         |         — |        — | ⬜ Not started |
| 16      | Structures, Unions, and Enumerations           |         — |        — | ⬜ Not started |
| 17      | Advanced Uses of Pointers                      |         — |        — | ⬜ Not started |
| 18      | Declarations                                   |         — |        — | ⬜ Not started |
| 19      | Program Design                                 |         — |        — | ⬜ Not started |
| 20      | Low-Level Programming                          |         — |        — | ⬜ Not started |
| 21      | The Standard Library                           |         — |        — | ⬜ Not started |
| 22      | Input/Output                                   |         — |        — | ⬜ Not started |
| 23      | Library Support for Numbers and Character Data |         — |        — | ⬜ Not started |
| 24      | Error Handling                                 |         — |        — | ⬜ Not started |
| 25      | International Features                         |         — |        — | ⬜ Not started |
| 26      | Miscellaneous Library Functions                |         — |        — | ⬜ Not started |
| 27      | Additional C99 Support                         |         — |        — | ⬜ Not started |

Status legend:

```text
⬜ Not started
🟨 In progress
🟩 Completed
```

---

## Notes

This repository contains my own implementations and solutions created while studying the book.

The book and its exercises are the work of **K. N. King** and their respective publisher.

This repository is intended for **educational and personal learning purposes**.

The original book should be used as the primary reference for the exercise and project statements.

---

## Reference

**K. N. King — C Programming: A Modern Approach, 2nd Edition**

The official author website provides additional information about the book, example programs, selected answers, and other resources.

---

## Goal

The main goal of this repository is simple:

> **Learn C by writing C.**

Rather than treating the book as something to read from beginning to end, this repository serves as a practical record of the problems I solve while progressing through the language.

Each chapter represents another step toward becoming more comfortable with C programming, from simple programs and expressions to pointers, memory management, data structures, low-level programming, and the standard library.

## License

The original code in this repository is licensed under the MIT License.

The MIT License applies only to the original code and materials created for
this repository. It does not apply to the book *C Programming: A Modern
Approach*, by K. N. King, or to its original copyrighted materials.

See the [LICENSE](LICENSE) file for the complete license.