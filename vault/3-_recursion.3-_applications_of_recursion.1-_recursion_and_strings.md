---
id: iyR0yOBJ88AClXfj5vszy
title: 1 _recursion_and_strings
desc: ''
updated: 1644767656943
created: 1644767656943
stub: false
isDir: false
---
# 1. Recursion and Strings
Created Thursday 02 January 2020

Some basic problems on strings using recursion:

1. Length of the string. Just do a head recursion. return 1 + length(input+1). Base case is the null character.
2. RemoveX(), we need to remove all 'x's in the given string.
	1. Shift by 1, that is O(n^2^) time. Memory O(1).
	2. Pass the write head, time O(n). Memory O(n) [Assuming we don't use pointers]. Or O(1) if references in the symbol table take constant space.
3. Remove duplicates, same as 2 except, that we do if(arr[0]==arr[1]) instead of if(arr[0]==x).


