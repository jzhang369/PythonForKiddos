---
marp: true
author: Junjie Zhang
theme: gaia
title: Introduction
paginate: true
---

# Data Types

+ Dr. Junjie Zhang
+ Huaxia Chinese School at Mason, OH

---

# Data Types

A variable can store data, which has a specific type. 

+ Built-In Data Types:
  + Known by the Python robot by default. 
+ Customized Data Types:
  + Designed by software engineers like you. 


---
# Built-In Data Types

+ Simple Data Types
  + integer, float, boolean, string, and etc. 
+ Complex Data Types
  + list, set, dict, and etc. 


---
# type()

If you want to know the type of data or data stored in a variable, use ``type()``.

```python
type("here")
type(29)
type(1.3)
type(True)
```
Let me know your outputs. 

---
# type()

If you want to know the type of data or data stored in a variable, use ``type()``.

```python
a = "here"
type(a)
a = 29
type(a)
a = 1.3
type(a)
a = True
type(a)
```
Let me know your outputs. 

---
# Types

+ **Int**, or integer, is a whole number, positive or negative, without decimals, of unlimited length.
+ **Float**, or "floating point number" is a number, positive or negative, containing one or more decimals.
+ **Booleans** represent one of two values: True or False.
+ **Strings** in python are surrounded by either single quotation marks, or double quotation marks.

---
# Two Important Questions

+ What data types matter?
  + The same operation may have different effectiveness with different data types.
  + Certain operations make sense only if they are applied on data with specific types. 
+ Can we convert one data type to another one? 
  + Yes to some of them. 


---
# Data Types Matter for Operators

Let's give a look at ``+``
```python
a = 1
b = 2
c = a + b
print(c)
```

```python
a = "1"
b = "2"
c = a + b
print(c)
```

---
# Data Types Matter for Operators

Let's give a look at ``*``
```python
a = 1
b = 2
c = a * b
print(c)
```

```python
a = "1"
b = "2"
c = a * b
print(c)
```
---
# Convert Data Types

A more professional way to say "data type converting" is **casting**!

---
# Python Casting

```python
x = int(1)   # x will be 1
y = int(2.8) # y will be 2
z = int("3") # z will be 3
```

---
# Python Casting

```python
x = float(1)     # x will be 1.0
y = float(2.8)   # y will be 2.8
z = float("3")   # z will be 3.0
w = float("4.2") # w will be 4.2
```

---
# Python Casting

```python
x = str("s1") # x will be 's1'
y = str(2)    # y will be '2'
z = str(3.0)  # z will be '3.0'
```

---
# More Discussion
+ Boolean
+ String