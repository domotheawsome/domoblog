---
title: "Binary Search: an Introduction and a Few Simple Problems"
date: 2022-08-22T00:31:52-07:00
draft: false
---

Introducing... Binary Search! This is a relatively simple algorithm that is often referred to as the "easiest of the complex algorithms". I have to agree. This is a divide-and-conquer algorithm with an O(log N) runtime that is easy to understand and implement, and most problems using binary search are just modifications of the core algorithm.

Divide-and-conquer algorithms are exactly how they sound; divide an array and conquer it. Take your array, break it into subarrays, and recursively repeat until you find your target. Via this method, it reduces the total search space by half each step.  

You achieve O(log N) time when you halve the array each recursion; if you recurse 3 times, you end up N/2, N/4, and N/8. Time goes up linearly while N elements goes up exponentially. It's also easy to recognize it's O(log N) as we are *choosing* the next element to perform an operation on. With slower runtimes-- O(N), O(N^2), O(N!), etc.-- you are checking *every* element rather than selecting an element. FYI, the only popular runtime faster than O(log N) is O(1).  

Binary search has lots of applications. 

Overall, binary search is a fundamental algorithm to apply to other more difficult problems. 