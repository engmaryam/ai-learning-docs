# 🐍 Python Basics for AI Engineering

Before diving into machine learning or deep learning, you need to build a strong foundation in Python. This guide covers essential Python concepts with short explanations and code examples.

---

## 📌 1. Variables and Data Types

```python
x = 10        # Integer
pi = 3.14     # Float
name = "AI"    # String
is_ready = True  # Boolean
```

---

## 📌 2. Lists, Tuples, and Dictionaries

```python
# List
fruits = ["apple", "banana", "mango"]

# Tuple (immutable)
point = (1, 2)

# Dictionary (key-value pairs)
person = {"name": "John", "age": 30}
```

---

## 📌 3. Conditional Statements

```python
if x > 5:
    print("x is greater than 5")
elif x == 5:
    print("x is 5")
else:
    print("x is less than 5")
```

---

## 📌 4. Loops

```python
# For loop
for fruit in fruits:
    print(fruit)

# While loop
count = 0
while count < 3:
    print(count)
    count += 1
```

---

## 📌 5. Functions

```python
def greet(name):
    return f"Hello, {name}!"

print(greet("AI Engineer"))
```

---

## 📌 6. Classes and Objects

```python
class Dog:
    def __init__(self, name):
        self.name = name

    def bark(self):
        print(f"{self.name} says woof!")

my_dog = Dog("Rex")
my_dog.bark()
```

---

## ✅ Practice Tips

* Write your code in **Jupyter Notebook** for quick testing
* Use `print()` often to understand outputs
* Try modifying the examples above

---

Next up: learn **Python for data handling** — `NumPy`, `Pandas`, and visualization libraries.

