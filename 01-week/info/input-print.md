# Using `input()` and `print()` in Python

One of the first things you’ll learn in Python is how to interact with users.
Python provides two simple and powerful functions for this:

- `input()` → receive information from the user
- `print()` → display information to the user

These functions form the foundation of almost every beginner program.

---

## 🟦 **1. The `print()` Function**

`print()` displays text or values on the screen.

### ✔ Basic Usage

```py
print("Hello, world!")
```

You can print multiple values:

```py
print("Your age is:", 25)
```

### ✔ Printing variables

```py
name = "Sam"
print("Hello,", name)
```

### ✔ f-strings (cleaner formatting)

```py
age = 30
print(f"You are {age} years old.")
```

---

## 🟩 **2. The `input()` Function**

`input()` lets your program receive user input as **text (string)**.

### ✔ Basic Input Usage

```py
name = input("Enter your name: ")
print("Hello,", name)
```

The message inside `input()` is the prompt shown to the user.

---

## 📌 **Important: `input()` Always Returns a String**

If you expect a **number**, you must convert it:

```py
age = int(input("Enter your age: "))
price = float(input("Enter the price: "))
```

---

## 🧪 **3. Simple Example Using Both**

```py
name = input("What is your name? ")
age = int(input("How old are you? "))

print(f"Hello {name}, you are {age} years old!")
```

---

## ⭐ **4. Common Patterns**

### ✔ Asking Multiple Questions

```py
first = input("First name: ")
last = input("Last name: ")

print("Welcome,", first, last)
```

### ✔ Doing Simple Math with Input

```py
num1 = int(input("Enter a number: "))
num2 = int(input("Enter another number: "))

print("Sum:", num1 + num2)
```

---

## 🎯 **5. Summary**

| Function  | Purpose                                    |
| --------- | ------------------------------------------ |
| `print()` | Displays output to the user                |
| `input()` | Receives input from the user (as a string) |

You will use `input()` and `print()` in almost every beginner-level program, and they remain useful even in advanced scripting and automation tasks.

---
