# Chapter 1: Binary Search - Lab Report

## Student Information
- **Name:** [Nathaniel Tryon]
- **Date:** [2/1/26]
- **Course:** COSC-2436 6001

## Algorithm Summary

### Linear Search
Linear Search is when we go through a list to look for a specified object and it starts to look from the start of the list and goes though the entire list until it finds the object. It’s slow but can work with unsorted lists with O(n) time complexity

### Binary Search
Binary Search is when we split a **sorted** list in half and the specified object we are looking for is either greater or lesser than the split and then with that half that’s greater or lesser we split it in half and find the greater or lesser half of that half this goes on until the object is found. Say we are looking for the number 87 in a list of 100 we split and check if 87 is greater or lesser than 50, it’s greater so we now split 50 - 100 which is 75, we split 75-100 is 87, number found 

## Test Results
Binary Search vs Linear Search Time Comparison
================================================
Searching in a sorted list of 128 numbers

Searching for: 1
Linear search time: 0.00000215 seconds
Binary search time: 0.00000262 seconds
Linear search result: 0
Binary search result: 0
Binary search is 0.82x faster

Searching for: 64
Linear search time: 0.00000501 seconds
Binary search time: 0.00000119 seconds
Linear search result: 63
Binary search result: 63
Binary search is 4.20x faster

Searching for: 128
Linear search time: 0.00000358 seconds
Binary search time: 0.00000238 seconds
Linear search result: 127
Binary search result: 127
Binary search is 1.50x faster

Searching for: 50
Linear search time: 0.00000191 seconds
Binary search time: 0.00000167 seconds
Linear search result: 49
Binary search result: 49
Binary search is 1.14x faster

Searching for: 100
Linear search time: 0.00000238 seconds
Binary search time: 0.00000095 seconds
Linear search result: 99
Binary search result: 99
Binary search is 2.50x faster

Searching for: 25
Linear search time: 0.00000191 seconds
Binary search time: 0.00000191 seconds
Linear search result: 24
Binary search result: 24
Binary search is 1.00x faster

Searching for: 75
Linear search time: 0.00000286 seconds
Binary search time: 0.00000215 seconds
Linear search result: 74
Binary search result: 74
Binary search is 1.33x faster

Searching for: 10
Linear search time: 0.00005937 seconds
Binary search time: 0.00000143 seconds
Linear search result: 9
Binary search result: 9
Binary search is 41.50x faster

Searching for: 90
Linear search time: 0.00000310 seconds
Binary search time: 0.00000191 seconds
Linear search result: 89
Binary search result: 89
Binary search is 1.62x faster

Searching for: 200
Linear search time: 0.00011206 seconds
Binary search time: 0.00000191 seconds
Linear search result: None
Binary search result: None
Binary search is 58.75x faster

Lab Challenge Answer:
Maximum steps for binary search in 128 items:
log2(128) = 7 steps maximum
