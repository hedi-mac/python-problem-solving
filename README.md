# Algorithms and Data Structures

This repository contains Python implementations of various algorithms and data structures.

## Table of Contents

1. [Valid Anagram](#valid-anagram)
2. [First and Last Index in Sorted Array](#first-and-last-index-in-sorted-array)
3. [Kth Largest Element](#kth-largest-element)

---

## Valid Anagram

### Method 1
- Checks if two strings are anagrams using frequency counting.
- Time complexity: O(n + m)

### Method 2
- Checks if two strings are anagrams using Python's Counter.
- Time complexity: O(n + m)

### Method 3
- Checks if two strings are anagrams by sorting and comparing.
- Time complexity: O(n * log(n))

---

## First and Last Index in Sorted Array

### Method 1 (Search)
- Finds the first and last index of a target in a sorted array.
- Time complexity: O(n + k)

### Method 2 (Binary Search)
- Finds the first and last index of a target in a sorted array using binary search.
- Time complexity: O(log n)

---

## Kth Largest Element

### Method 1
- Finds the Kth largest element in an array by repeatedly removing the maximum element.
- Time complexity: O(kn)

### Method 2 (Sorting)
- Finds the Kth largest element in an array by sorting and indexing.
- Time complexity: O(n log n)

### Method 3 (Heap)
- Finds the Kth largest element in an array using a min-heap.
- Time complexity: O(n + k log n)

---

Feel free to explore the code implementations for each method in the respective sections. If you have any questions or need further details, refer to the code or reach out to the repository owner.

Happy coding!
