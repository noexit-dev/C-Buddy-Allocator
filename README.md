# Buddy Memory Allocator (C)

* Author: Rylee Hilde
* Semester: Fall 2026

## Overview

This program implements a Buddy Allocator memory management system that functions in user space.

## Usage

To compile the program please navigate to the project directory and run the following command:

```make
make
```

To run the program run the following command:

```make
make run
```
## Results

When running main.c it tests the following:

- Allocation of incorrect size
- Two allocations from the same pool
- Two frees from the same pool
- There is some print functionality that is commented out that show bitmap and head addresses for the freelist, but are not used for readablity

DEQ (Doubly-Linked Double-Ended Queue) tests using wrapper.c
- Adding nodes from the head and tail using Put
- Removing nodes from the head and tail using Get
- Removing from an empty list using Get
- Searching and Removing from an empty list using Ith and Rem
- Searching and Removing from a populated list using Ith and Rem
- Searching and Removing the edges (Head or Tail) from a populating list using Ith and Rem

These tests simply highlight the behavior of the implemented methods and do not show whether the behavior is correct. It is up to the person that runs main to see if the behavior is correct. As this was mainly a tool for the developer (me), I believe that the behavior of my tests are correct and tests for most cases. 

----------
