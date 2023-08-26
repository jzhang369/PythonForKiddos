---
marp: true
author: Junjie Zhang
theme: gaia
title: Introduction
paginate: true
---

# Variables

+ Dr. Junjie Zhang
+ Huaxia Chinese School at Mason, OH

---

# Variables

A variable is a container/box for storing a data value.

![bg right](https://i.etsystatic.com/7410674/r/il/1162cc/3856557803/il_794xN.3856557803_kvgj.jpg)


---
# An Example

``
x = 1
``

+ What does this mean? Any thoughts? 
+ What does "**=**" mean? Please clarify. 

---
### "**=**" might be mind-blowing for kiddos

It was definitely mind-blowing for me when I was 18. 

+ In programming, "**=**" is for **assign**, NOT for **equal**
+ Put the data from the right side to the left side

---
# A Few Examples

```python
x =1 
print(x)
```

```python
x = 1
y = x 
print(x)
print(y)
```

```python
x = 1
y = x + 1
print(x)
print(y)
```

---
# A Few Examples

```python
x = 1
x = x + 1 
print(x)
```


```python
name = input("please enter your name")
print(name)
```

---
### Rules for Python Variables (Not Important. Just FYI)

+ A variable name must start with a letter or the underscore character
+ A variable name cannot start with a number
+ A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
+ Variable names are case-sensitive (age, Age and AGE are three different variables)

---

# Why do we need variables? 

Can't we just work on numbers?

```python
x = 100
y = 200
z = x + y
print(z)
```

Why bothoring? I can simply write the following and I still rock!

```python
z = 100 + 200 
print(x)
```

---

# Why do we need variables? 

A math puzzle:
+ The first number is 2345
+ The second number 5432
+ What is the result when you add these two numbers, their mutiplication result,  the first one times 12, and the second one times 50? 

---
# Why do we need variables? 

### Easy Peasy Lemon Squezzy!

```python
result = 2345  + 5432 + 2345 * 5432 + 2345 * 12 + 5432 * 50
print(result)
```

---
# Why do we need variables? 
But I may have the same type puzzle with different values for the first number and second number. 

Aother one: The first number is 234; The second number 543; ....
Yet another one: The first number is 666; The second number 888; ....
Yet another one: The first number is 777; The second number 999; ....

---
# Why do we need variables? 
What's the problem now? 

```python
result = 234  + 543 + 234 * 543 + 234 * 12 + 543 * 50
print(result)
```

```python
result = 666  + 888 + 666 * 888 + 666 * 12 + 888 * 50
print(result)
```

```python
result = 777  + 999 + 777 * 999 + 777 * 12 + 999 * 50
print(result)
```
---
![bg](https://static4.depositphotos.com/1004125/317/i/950/depositphotos_3170807-stock-photo-crazy-typing.jpg)

---
# Why do we need variables? 

They help to isolate the pattern of calculation from the specific numbers for this example. **So that you can reuse your code!**

```python
num1 = 2345
num2 = 5432
result = num1  + num2 + num1 * num2 + num1 * 12 + num2 * 50
print(result)
```

---
### And it eases your life!

```python
num1 = 234
num2 = 543
result = num1  + num2 + num1 * num2 + num1 * 12 + num2 * 50
print(result)
```

```python
num1 = 666
num2 = 888
result = num1  + num2 + num1 * num2 + num1 * 12 + num2 * 50
print(result)
```

```python
num1 = 777
num2 = 999
result = num1  + num2 + num1 * num2 + num1 * 12 + num2 * 50
print(result)
```
---
# Questions? 


---
# Quiz

Quiz 1:

+ The first number is 333
+ The second number is 444
+ The addition of 1) the first number times the second number, 2) the square of the first number, and 3) the square of the second number. 
  + 333 * 444 + 333 * 333 + 444* 444
+ Print the result

Quiz 2: Repeat Quiz 1 using two different numbers: 111 and 222

---
# Another Exercise

```python
x = 111
y = 888
print(x)
print(y)

#write your code here

print(x)
print(y)
```

Complete the code here to swap values in *x* and *y*. 

---
# Homework
```python
x = 111
y = 222
z = 333
print(x)
print(y)
print(z)
#write your code here
print(x)
print(y)
print(z)
```
After your code executes, x will have y's value, y will have z's value, and z will have x's value. 

---
# Questions? 
