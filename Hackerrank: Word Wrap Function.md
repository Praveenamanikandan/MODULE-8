#  Hackerrank : #  Python Word Wrap Function


---

##  Aim

Write a python program to display elements from a list, present at odd index positions


---

##  Algorithm

Start

Define a class with required data members.

Create a constructor to initialize the data members.

Define the operator overloading method (__add__) to perform the desired operation (here, complex number division).

Return the result as a new object of the same class.

Define a method to display the result in a readable format.

Create objects of the class with initial values.

Use the overloaded operator between the objects to perform the operation.

Display the final result.

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
