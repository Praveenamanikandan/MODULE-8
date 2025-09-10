#  Hackerrank:Runner-Up Score Finder in Python

##  AIM:
Develop a python program to square all the even numbers and cube all odd numbers from a list of integers. Get the starting and ending range to create a list


---

##  ALGORITHM:

Start

Define the problem to be solved.

Identify the inputs required.

Identify the process/steps needed to solve the problem.

Identify the outputs to be produced.

Write the steps in logical order:

Accept input.

Perform the necessary computations or processing.

Produce and display the output.

Stop
---

##  PROGRAM:
```
cube = lambda x: x**2 if x%2==0 else x**3
def fun(f,l):
    l1=[]
    for i in range(f,l+1):
        l1.append(i)
    return l1
f,l = int(input()),int(input())

```

## OUTPUT
<img width="939" height="169" alt="image" src="https://github.com/user-attachments/assets/41615c35-cafc-4f47-b0f8-aaa4949422e5" />

## RESULT
The Program was executed successfully
