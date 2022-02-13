---
id: hnc6ZBEMRcx5mIvPHPvDQ
title: 7 _question_ _infinite_stream
desc: ''
updated: 1644767656951
created: 1644767656951
stub: false
isDir: false
---
# 7. Question - Infinite Stream
Created Tuesday 18 February 2020

Q) We are given an array(always finite) of integers. An infinte stream of integers is coming, we have to say for every integer "have we seen that before"?
A) One possible wrong way is that we store the all integers as indexes of a boolean array. If a number is present, return true. If not, mark it true.

* This is wrong because it wastes a lot of space.(Because size required = maximum element in the array).
* Maps are the best for this, we can use negative as well as too large numbers, space requirement is the same.


