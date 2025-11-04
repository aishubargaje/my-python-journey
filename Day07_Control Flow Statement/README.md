# 🧠 Day 07 - Control Flow Statements (Loops & Conditional Statements)

### 🚀 Topic: Loops, If-Else, Break & Continue in Python

---

## 📚 Overview

In Python, **control flow statements** determine the order in which statements are executed in a program.  
Today’s focus is on:
- ✅ Decision-making using `if`, `elif`, and `else`
- 🔁 Repetitive tasks using `for` and `while` loops
- ⏸️ Controlling loop behavior using `break`, `continue`, and `pass`

---

## 🧩 Topics Covered

### 1️⃣ If-Else Statements
Used for decision making based on conditions.

```python
x = 10
if x > 0:
    print("Positive number")
elif x == 0:
    print("Zero")
else:
    print("Negative number")

### 2️⃣ For Loop

Used to iterate over a sequence (like a list, tuple, or string).

for i in range(5):
    print("Iteration:", i)

### 3️⃣ While Loop

Executes a block of code as long as a condition is true.

count = 0
while count < 5:
    print("Count:", count)
    count += 1

### 4️⃣ Break Statement

Used to exit a loop immediately.

for i in range(10):
    if i == 5:
        break
    print(i)

### 5️⃣ Continue Statement

Skips the current iteration and moves to the next one.

for i in range(5):
    if i == 2:
        continue
    print(i)

### 6️⃣ Pass Statement

Acts as a placeholder for future code.

for i in range(3):
    pass  # To be implemented later
