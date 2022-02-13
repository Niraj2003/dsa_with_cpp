---
id: 938oj6D7wOc2vKveQ0Y3p
title: 4 _recursion_with_arrays
desc: ''
updated: 1644767656943
created: 1644767656943
stub: false
isDir: false
---
# 4. Recursion with Arrays
Created Saturday 28 December 2019


* Some problems are very tedious to solve using iterative methods, they may ultimately require a programmers stack. 
* Difference between head recursion and tail recursion.

e.g check if given array is sorted or not
 Method 1: if(n<=1) return true.
if arr[0]<=arr[1] check further in f(arr+1, n-1)
else return false;
// it will ultimately reach n-1.
**Tail recursion. Easier to convert to an iteration.**
Method 2: if(n<=1) it is sorted by default.
if(f(arr+1, n-1)==true)
{
if(arr[0] <=arr[1]
return true;
}
return false;
**Head recursion.** **Difficult to convert to an iteration.**



