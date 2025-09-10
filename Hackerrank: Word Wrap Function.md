#  Hackerrank : # Python Word Wrap Function

Find the simple interest by getting the principal, rate and time value from the user


---

##  Aim

To write a Python function that takes a long string and a specified width, and returns the string formatted with line breaks such that each line has *at most the given width*.

---

##  Algorithm

Start

Define a class with required data members.

Create a constructor to initialize the data members.

Define the operator overloading method (_add_) to perform the desired operation (here, complex number division).

Return the result as a new object of the same class.

Define a method to display the result in a readable format.

Create objects of the class with initial values.

Use the overloaded operator between the objects to perform the operation.

Display the final result.

---


##  Program
```
def simpleInterest(p, t, r):
    return (p * t * r) / 100

# Getting user input
p = float(input())
r = float(input())
time_input = input()

# Convert time to float (handle fractional input like 9/12)
if '/' in time_input:
    num, denom = map(float, time_input.split('/'))
    t = num / denom
else:
    t = float(time_input)
```

## Sample Output
<img width="1047" height="241" alt="image" src="https://github.com/user-attachments/assets/111bcc43-9581-43f3-a011-125c78933e90" />

## Result

The program was executed successfully
