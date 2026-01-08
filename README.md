# RU Kindergarten (Java)

## Overview
RU Kindergarten is a Java project that simulates a kindergarten classroom using **multiple data structures**, each chosen based on the type of classroom behavior being modeled. The project demonstrates how different data structures are applied together in a single system to represent real-world scenarios.

The primary focus of the assignment is **data structure design and implementation**, rather than user interface development.

---

## Project Structure
src/
  kindergarten/
    Classroom.java
    Driver.java
    Student.java
    SNode.java
    StdIn.java
    StdOut.java
    StdRandom.java

---

## Data Structures Used
- **Singly linked list** – managing students in line
- **Circular linked list** – rotating students during classroom activities
- **2D array** – representing classroom seating arrangements

---

## Key Classes

### `Classroom`
Implements the core classroom logic and manages interactions between different data structures. This class is responsible for organizing students, handling seating, and coordinating classroom activities.

### `Student`
Represents an individual student and stores relevant student information.

### `SNode`
Node class used to build linked list structures.

### `Driver`
Acts as the main entry point for the program and coordinates input/output for the simulation.

### Standard I/O Utilities
- `StdIn`
- `StdOut`
- `StdRandom`

These classes provide helper methods for input, output, and randomization.

---

## Features
- Manage students using linked list structures
- Rotate students using a circular linked list
- Assign and organize students in a classroom seating chart
- Demonstrates appropriate selection of data structures for different tasks

---

## How to Run

### Compile
```bash
javac src/kindergarten/*.java
```

---

## What I learned
How to design systems that use multiple data structures together
Practical differences between singly linked lists and circular linked lists
When arrays are more suitable than linked structures
Writing code that integrates with existing scaffolding and interfaces

---

## Notes
Classroom.java was implemented as part of the course assignment.
Supporting files (Driver, Student, SNode, and standard I/O utilities) were provided as scaffolding and were not modified.
