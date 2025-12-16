# CS50 PROBLEM SET 3 - Sort

This repository contains my solution for the Sort problem from Harvard's CS50 Problem Set 3. The task was to analyze three unknown sorting programs and determine which sorting algorithm each one uses based on their performance on different types of input data.

## Files

- `answers.txt` : Contains my conclusions about which sorting algorithm is used by each program and the reasoning behind each decision.
- sort1 : Compiled sorting program (provided by CS50).
- sort2 : Compiled sorting program (provided by CS50).
- sort3 : Compiled sorting program (provided by CS50).

## Input Data Files

The repository also includes multiple input datasets used for testing performance:

- `random5000.txt`
- `random10000.txt`
- `random50000.txt`
- `sorted5000.txt`
- `sorted10000.txt`
- `sorted50000.txt`
- `reversed5000.txt`
- `reversed10000.txt`
- `reversed50000.txt`

These files contain integers in random, sorted, and reverse-sorted order.

## Description

The goal of this problem set was not to write a sorting algorithm, but to analyze the runtime behavior of three provided programs and identify which sorting algorithm each one implements.

I tested each program against:

- Random data
- Already sorted data
- Reverse-sorted data

By comparing execution speed across these scenarios, I was able to infer the underlying algorithm used by each program.

## Determined Sorting Algorithms

Based on performance analysis:

sort1 uses Bubble Sort

- Faster on already sorted input
- Performs similarly to Selection Sort on unsorted data

sort2 uses Merge Sort

- Fastest in all scenarios
- Consistent performance regardless of input order

sort3 uses Selection Sort

- Slower on sorted input compared to Bubble Sort
- Performance remains consistently slower across datasets

These conclusions are documented in detail in answers.txt.

## Skills Demonstrated

Algorithm analysis

Time complexity reasoning

Empirical performance testing

Understanding differences between Bubble Sort, Selection Sort, and Merge Sort

Interpreting runtime behavior without access to source code
