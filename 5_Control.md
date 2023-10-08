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
    print("Do you feel the bitter tase?")
else:
    print("Kiddo, I can only offer you milk.")
    print("Do not forget to say thank you.")
    print("You are welcome!")
```


