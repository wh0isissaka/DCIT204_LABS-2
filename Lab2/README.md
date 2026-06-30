# Lab 2 – Interactive Array Algorithms

**Course:** DCIT 204
**Student:** [Imoru Issaka Shaibu] – [22300020]

## Overview
This project implements two interactive Java console programs using arrays, loops, and the `Scanner` class.

## Files
- `FindMax.java` — Finds the maximum value in a user-entered array and its index.
- `PairSum.java` — Searches for a pair of numbers in a user-entered array whose sum equals a target value, using a brute-force nested-loop approach.

## How to Run

### FindMax
```bash
javac FindMax.java
java FindMax
```

### PairSum
```bash
javac PairSum.java
java PairSum
```

## Time Complexity
- **FindMax:** O(n) — single pass through the array.
- **PairSum (Brute Force):** O(n²) — nested loop checks every pair of elements.s