# Primitive Data Types in Python

Python provides several basic (primitive) data types that you’ll use in almost every program. These types represent
simple values such as numbers, text, and logical states.

The four most common primitive types are:

- `int` → integers
- `float` → decimal numbers
- `str` → text (strings)
- `bool` → true/false values

---

## 🔢 **1. `int` — Integer**

An **integer** represents whole numbers (positive, negative, or zero).

Examples:

```py
age = 25
year = 2025
temperature = -3
```

Use `int` when you don’t need decimals.

---

## ➗ **2. `float` — Floating-Point Number**

A **float** represents numbers with decimals.

Examples:

```py
height = 1.75
price = 9.99
pi = 3.14159
```

Use `float` when precision with decimals is important.

---

## 📝 **3. `str` — String**

A **string** represents text.
Strings are written inside quotes (`" "` or `' '`).

Examples:

```py
name = "Sam"
message = 'Hello, Python!'
country = "Belgium"
```

Strings can contain letters, numbers, and symbols.

---

## ✅ **4. `bool` — Boolean**

A **boolean** represents a logical value:

- `True`
- `False`

Examples:

```py
is_admin = True
is_student = False
```

You’ll use booleans often in conditions and decision-making.

---

## 🧪 **Quick Example Using All Types**

```py
name = "Alice"     # str
age = 30           # int
height = 1.68      # float
is_active = True   # bool

print(name, age, height, is_active)
```

---

## 📌 Notes

- Python is dynamically typed → you don’t need to declare types manually
- You can check a variable’s type using:

```py
print(type(age))
```

---

## 🎯 Summary

| Type    | Meaning         | Example   |
| ------- | --------------- | --------- |
| `int`   | Whole numbers   | `42`      |
| `float` | Decimal numbers | `3.14`    |
| `str`   | Text            | `"Hello"` |
| `bool`  | True/False      | `True`    |

These primitive types form the foundation of Python programming.
You will combine them to create more complex logic and data structures in later weeks.

---
