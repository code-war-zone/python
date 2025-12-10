# **Type Conversion Basics in Python**

In Python, data often comes in different formats — numbers, text, booleans, user input, etc.
**Type conversion** allows you to change a value from one data type to another so you can use it correctly in your program.

---

## 🔄 **Why Type Conversion Matters**

- User input always comes in as a **string**
- Math only works with **numbers**
- Boolean checks may require converting values
- Data processing often requires switching between types

Example:

```py
age = input("Enter your age: ")
# age is a string → convert to int
age = int(age)
```

---

# 🔧 **Built-In Conversion Functions**

Python provides several simple functions for converting data types.

---

## **1. `int()` – Convert to Integer**

Converts a value to an integer (whole number).

```py
int("10")     # 10
int(3.99)     # 3
```

---

## **2. `float()` – Convert to Float**

Converts to a decimal number.

```py
float("5.5")  # 5.5
float(10)     # 10.0
```

---

## **3. `str()` – Convert to String**

Converts any value to text.

```py
str(25)       # "25"
str(True)     # "True"
```

---

## **4. `bool()` – Convert to Boolean**

Converts a value into `True` or `False`.

```py
bool(1)       # True
bool(0)       # False
bool("")      # False
bool("Hi")    # True
```

General rule:

- Empty values → `False`
- Non-empty values → `True`

---

# 📌 **Common Use Case: User Input**

Since `input()` always returns a **string**, conversion is often required:

```py
price = float(input("Enter price: "))
quantity = int(input("Enter quantity: "))

total = price * quantity
print("Total:", total)
```

---

# 🧪 **Quick Practice**

Try converting the following:

- `"123"` → integer
- `"3.14"` → float
- `45` → string
- `"hello"` → boolean
- `0` → boolean

---

# 🎉 **Summary**

| Conversion | Function  | Example         |
| ---------- | --------- | --------------- |
| To integer | `int()`   | `int("10")`     |
| To float   | `float()` | `float("3.14")` |
| To string  | `str()`   | `str(25)`       |
| To boolean | `bool()`  | `bool("hi")`    |

Type conversion ensures your data is in the correct format for the operation you want to perform.

---
