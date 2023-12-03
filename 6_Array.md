---
marp: true
author: Junjie Zhang
theme: gaia
title: Control
paginate: true
---

# List

+ Dr. Junjie Zhang
+ Huaxia Chinese School at Mason, OH


---
# A list variable

![](https://www.keystonesafe.com/cdn/shop/products/lat4w44p-01.jpg?v=1697734565&width=550)

---

# List is a data type
 
+ A variable of the list type is used to store mulitple items in a single variable.
+ It is one of four built-in data types for store mutiple items in a single variable. 
  + List
  + Tuple
  + Set
  + Dictionary

---
# List

```python
mylist = ["apple", "banana", "cherry"]
print(mylist)
```

---
# A list variable allows duplicates

```python
mylist = ["apple", "banana", "banana", "cherry"]
print(mylist)
```

---
# size of a list variable (or number of elements)

Using a funciton called ```len()```

+ len(mylist)

---
# Accessing a list variable using index

An index is an integer

- First element is indexed by 0
- Last element is indexed by len -1

What happens if you read an element from a list using index greater than len -1? 


---
# Declaring a variable as a list variable with no element

```python
a = []
```

---
# Do all elements in the same list variable need to have the same type?

```python
a = [11, 22, 33, 44]
b = ["you", "are", "not", "welcome"]
c = [True, True, False, False]
```

How about 
```python
d = [44, "are", False]
```

Elements in the same list variable do not have to have the same type. This is not frequently used, but this is allowed. 

---
# Quiz

```python
a = [1, 2.5, "welcome", False]
# write your code to 
# print the size of a
# print the type of a
# print the type of the first element in a
# print the type of the last element in a
```

---
# Change An Item in a List Variable

```python
a = [1, 2.5, "welcome", False]
print(a)
a[0] = "not"
```

---
# Insert an iterm at a certain index

```python
thislist = ["apple", "banana", "cherry"]
thislist.insert(2, "watermelon")
print(thislist)
```

---
# Append an iterm to a list variable

```python
thislist = ["apple", "banana", "cherry"]
thislist.append("orange")
print(thislist)
```

---
# Remove Specified Item Using the Item itself
```python
thislist = ["apple", "banana", "cherry"]
thislist.remove("banana")
print(thislist)
```

---
# Remove Specified Item using an index

```python
thislist = ["apple", "banana", "cherry"]
item = thislist.pop(1)
print(thislist)
print(item)
```

When you do not specify the index, it removes the element from the end. 

```python
thislist = ["apple", "banana", "cherry"]
item = thislist.pop()
print(thislist)
print(item)
```

---
# Delete all items in a list variable

```python
thislist = ["apple", "banana", "cherry"]
thislist.clear()
print(thislist)
```

---
# Sort items in a list variable in the ascending or the decending order 

```python
thislist = [100, 50, 65, 82, 23]
thislist.sort()
print(thislist)
```

```python
thislist = [100, 50, 65, 82, 23]
thislist.sort(reverse = True)
print(thislist)
```


