# Day 02 - Operators in Python ➗✖️➕➖

## 📌 Description
On **Day 02** of my Python journey, I practiced using **operators** by solving some basic math problems.  

In Python, operators are special symbols that perform operations on variables and values.  
They are the building blocks of programming because almost every program needs calculations or comparisons.  

The problems I solved are:  
1. **Add Two Numbers**  
2. **Find the Square Root**  
3. **Calculate the Area of a Triangle**  
4. **Solve a Quadratic Equation**

---

## 🖥️ Code

```python
# Day 02 - Basic Math Problems
# Author: Aishwarya
# Date: Day 02 of Python Journey

import cmath  # for handling complex numbers in quadratic equations

# 1️⃣ Add Two Numbers
num1 = 10
num2 = 20
print("Addition of two numbers:", num1 + num2)

# 2️⃣ Find Square Root
number = 16
sqrt = number ** 0.5
print("Square root of", number, "is:", sqrt)

# 3️⃣ Calculate Area of Triangle
a = 5
b = 6
c = 7
s = (a + b + c) / 2  # semi-perimeter
area = (s*(s-a)*(s-b)*(s-c)) ** 0.5
print("Area of triangle is:", area)

# 4️⃣ Solve Quadratic Equation: ax² + bx + c = 0
a = 1
b = 5
c = 6
d = (b**2) - (4*a*c)  # discriminant
root1 = (-b - cmath.sqrt(d)) / (2*a)
root2 = (-b + cmath.sqrt(d)) / (2*a)
print("Quadratic equation roots are:", root1, "and", root2)

