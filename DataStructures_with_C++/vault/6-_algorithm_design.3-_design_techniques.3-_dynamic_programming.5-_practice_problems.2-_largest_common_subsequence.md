---
id: iTObz4YwF86jRkg4rhBgZ
title: 2 _largest_common_subsequence
desc: ''
updated: 1644767656955
created: 1644767656955
stub: false
isDir: false
---
# 2. Largest Common Subsequence
Created Monday 16 March 2020

[LCS.cpp](./Codes/LCS.cpp)

In LCS we use the basic methodology of string recursion. This works like a charm because at the end of the day. We can see only an atomic part of the string. 

Either the letter is present or it is not.

If  
return 1 + LCS(a.substring(1), b.substr())
else
return max(LCS(a.substr(1), b), LCS(a, b.substr(1))


