# #  Hackerrank:#  Student Topper Finder


---

##  Aim

Find the simple interest by getting the principal, rate and time value from the user


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

##  PROGRAM:
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
## OUTPUT
<img width="1155" height="254" alt="image" src="https://github.com/user-attachments/assets/2c979850-90b6-49c7-929c-5b9bcf98e4d5" />

## RESULT
The Program was executed successfully
