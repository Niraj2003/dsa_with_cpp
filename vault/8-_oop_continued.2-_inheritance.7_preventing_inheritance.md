---
id: gmeQPNlao7qV4tVPQAxeu
title: 7_preventing_inheritance
desc: ''
updated: 1644767656946
created: 1644767656946
stub: false
isDir: false
---
# 7. Preventing inheritance
Created Monday 04 February 2022

If we don't want a class to be derived from anymore, we can specify this using the `final` modifier, like so:
```c++
class First final
{
	// usual code here
};
```
OR if we are a derived class
```c++
class Car final : public Vehicle
{
	// usual code here
};
```

Deriving from a class modified as `final` is error.
