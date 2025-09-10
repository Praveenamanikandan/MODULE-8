#  Hackerrank : #  Python Word Wrap Function


---

##  Aim

Write a python program to display elements from a list, present at odd index positions


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


## 🧪 Program
```
# Read the number of elements
n = int(input())

# Read the elements into a list
lst = []
for i in range(n):
    element = int(input())
    lst.append(element)

# Display elements at odd index positions
for i in range(1, len(lst), 2):
    print(lst[i], end=" ")

```

## Sample Output
<img width="403" height="313" alt="image" src="https://github.com/user-attachments/assets/4a3bd964-9aa6-45a4-8704-45cb2e62d9ef" />

## Result
The Program was executed successfully
