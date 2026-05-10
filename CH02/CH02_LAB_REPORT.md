[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=22540392&assignment_repo_type=AssignmentRepo)
# Chapter 02: Selection Sort - Lab Report

## Overview
Implement selection sort and understand arrays vs linked lists.

## Learning Objectives
- Implement selection sort O(n²)
- Understand array vs linked list tradeoffs
- Analyze algorithm complexity

## Files to Complete
- `sort.py` - Implement `find_smallest()` and `selection_sort()` functions

## Instructions

### Part 1: Implement find_smallest
Find the index of the smallest element in a list starting from a given position.

### Part 2: Implement selection_sort
Use find_smallest to implement selection sort from Chapter 2.

### Part 3: Run Tests
```bash
python -m pytest tests/ -v
```

---

## Lab Report

### Student Information
- **Name:** Nathaniel Tryon
- **Date:** 2/8/26

### Algorithm Analysis

#### Selection Sort
- **Time Complexity:** O(n^2)
- **How it works:** [Your explanation]

#### Arrays vs Linked Lists

| Operation | Array | Linked List | Why? |
|-----------|-------|-------------|------|
| Read      |O(1)|O(n)|To read a linked list you need to read the previous items address and go there|
| Insert    |O(n)|O(1)|To insert a item in a Array all other items must shift|
| Delete    |O(n)|O(1)|For a list we can change what the previous element points to|

### Reflection Questions

1. Why is selection sort O(n²)?
It needs to sort through 2 different lists to get an O(n x n). So say we need to go through one array then after that we then need to sort an array that is linked to that first list. So the first is O(n) and then another array a O(n)

2. When would you choose a linked list over an array?
To do quick inserts and deletes and for a memory cost saving measure because they don't waste memory space like arrays can.
