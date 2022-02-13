---
id: pe1NhHPh1UbDAUZwtLkFK
title: 5 _approach_for_recursive_problems
desc: ''
updated: 1644767656943
created: 1644767656943
stub: false
isDir: false
---
# 5. Approach for recursive problems
Created Saturday 28 December 2019

To solve a recursive problem

* Find a base case
* Find a solution for the solution in terms of itself (Hypothesis). Very exhilarating step.
* Solve the question.
* If possible, use **tail **recursion. As it can easily be converted to iterative if required.


Q) We have been given an integer array and a number 'x'. We need to find the first index of the occurence of 'x', if it is present. Otherwise return -1.
A) We can do both tail recursion and head recursion. But as we need to find the 'first' occurrence. Hence we are better off with tail recursion.

