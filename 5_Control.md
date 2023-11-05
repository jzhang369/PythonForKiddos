---
marp: true
author: Junjie Zhang
theme: gaia
title: Control
paginate: true
---

# Control

+ Dr. Junjie Zhang
+ Huaxia Chinese School at Mason, OH

---

# Control

A *Control* statement instrument the Python robot to take action based on a certain condition. 

+ Conditional Branch
  + if else
  + if elif else
  + match case
+ Loop
  + while
  + for

---
# if-else / if-elif-else

Some examples of conditional braching:

+ If I am hungry, I will eat, otherwise I will play. 
+ If your age is above 6, you want coffee, otherwise you want milk. 
+ If your dad is angry, you shut up, otherwise keep whining. 

---
# if-else / if-elif-else

Some examples of conditional braching:

+ If your age is above 6, you want coffee, otherwise you want milk. 

What is the pattern?
```python
if cond:
    #take action when the cond can be satisified (i.e., cond is true)
else:
    #take action when the cond cannot be satisified (i.e., cond is false)
```

---
# if-else

```python
if cond:
    #take action when the cond can be satisified (i.e., cond is true)
else:
    #take action when the cond cannot be satisified (i.e., cond is false)
```

Love it or Hate it: now you need to know Python indentation. 


---
## Watch out, the Python indentation is coming!

![bg width:500px](https://www.codesdope.com/pa-images-bucket/courses/python/if2.jpg)

---
## Watch out, the Python indentation is coming!

![bg width:500px](https://www.codesdope.com/pa-images-bucket/courses/python/if3.jpg)

---
# if-else / if-elif-else

Alright, a quiz, some elements are given below. 
+ Take an input from the terminal, asking for your age 
+ If your age is above 6, say ```I can offer you coffee.```
+ Otherwise, say ```Kiddo, I can only offer milk.```

```python
age = input("Let me know your age:")
age = int(age)
print("I can offer you coffee.")
print("Kiddo, I can only offer you milk.")
```
---
# if-else / if-elif-else

```python
age = input("Let me know your age:")
age = int(age)
if age > 6: 
    print("I can offer you coffee.")
else:
    print("Kiddo, I can only offer you milk.")
```

---
# if-else / if-elif-else

```python
age = input("Let me know your age:")
age = int(age)
if age > 6: 
    print("I can offer you coffee.")
    print("Do you feel the bitter?")
else:
    print("Kiddo, I can only offer you milk.")
    print("Do not forget to say thank you.")
    print("You are welcome!")
```

---
# if-else / if-elif-else

Alright, another quiz, some elements are given below. 
+ Take an input from the terminal, asking for your age 

+ If the age is smaller than 6, say ```Kiddo, I can only offer milk.```
+ If your age is >= 6 but smaller than 18 , say ```I can offer you coffee.```
+ If your age is >= 18 but smaller than 18 , say ```I can offer you wine.```

---
# Solution 1
```python
age = input("Let me know your age:")
age = int(age)
if age < 6: 
    print("I can offer you milk.")

if age >= 6 and age < 18:
    print("I can offer you coffee.")

if age >= 18: 
    print("I can offer you wine.")
```

---
# Solution 2
```python
age = input("Let me know your age:")
age = int(age)
if age < 6: 
    print("I can offer you milk.")
elif age < 18:
    print("I can offer you coffee.")
else: 
    print("I can offer you wine.")
```
Benefits: more efficient, more concise, more coherent. 

---
# Loop

+ while
  + this is going to be our focus
+ for

---
# while

```python
while cond:
    #action
```

Repeatedly execute the ```action``` when ```cond``` is true. 

---
# while

Example: print 1, 2, 3, .... 1000

How can you do it?

```python
print(1)
print(2)
...
print(1000)
```

![bg right:50%](https://martech.org/wp-content/uploads/2014/08/typing-writing-blogging-content-ss-1920.jpg)

---
# while

Example: print 1, 2, 3, .... 1000

```python
i = 1
while i <= 999:
    print(i)
    i = i + 1
```

---
# while

Example: print 1000, 999, ... 1

```python
i = 1000
while i >= 2:
    print(i)
    i = i - 1
```

---
# while

Quiz 1: print 10, 11, 12, ... 20


---
# while

Quiz 2: print 2, 4, 6, ... 100

---
# while

Quiz 3: print a number between 1 and 100 if it is divisible by 3. 

Hint: ```%``` is an arithmetic operation to get the remainder of a division. 

Example: 
+ 3 % 3 is 0, 
+ 9 % 3 is 0, 
+ 10 % 3 is 1.  

---
# while

Quiz 4: decide whether a number is a prime number. 

