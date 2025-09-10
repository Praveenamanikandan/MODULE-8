#  Hackerrank:Python Program to Find Students with the Second Lowest Grade


---

##  Aim

Given the names and grades for each student in a class of  students, store them in a nested list and print the name(s) of any student(s) having the second lowest grade.
---

##  Algorithm

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

##   Program

```
n=int(input())
l=[]
a=[]
for i in range(n):
    l+=[[input(),float(input())]]
l.sort(key=lambda x:x[1])
smax=l[1][1]
for i in range(n):
    if l[i][1]==smax:
        a.append(l[i][0])
a.sort()
for i in a:
    print(i)
```
## Output
<img width="410" height="367" alt="image" src="https://github.com/user-attachments/assets/3d950d3e-36be-45a0-b2fd-6a57e201abb6" />

## Result

The Program was executed successfully



