---
id: eXSrsTpi21pLa4J32QJOE
title: 4 _reverse_ll(recursive)
desc: ''
updated: 1644767656953
created: 1644767656953
stub: false
isDir: false
---
# 4. Reverse LL(recursive)
Created Saturday 18 January 2020

This is the most plain recursive method.

* Here we return the head of the LL.
* Connect the node in the current activation record and add it to the end, yes we would require traversing the LL for this.
* Put the head->next = NULL. As it has become the last node of the LL.
* Return the head of the LL.

Time Complexity  = o(n^2^)
This could be sped up, return the head and the last pointer both. i.e two pointers

