# Complex Data Types in Python

In addition to primitive data types, Python provides **complex (or composite) data types** that allow you to store and
organize multiple values together. These data structures are essential for handling real-world data and building more advanced programs.

The main complex data types in Python are:

- `list`
- `tuple`
- `set`
- `dict` (dictionary)

Each type has a specific purpose and use case.

---

## 📚 **1. List**

A **list** is an ordered, changeable (mutable) collection of items.

- Defined using square brackets `[]`
- Can contain mixed data types
- Allows adding, removing, or modifying elements

Example:

```py
fruits = ["apple", "banana", "cherry"]
numbers = [1, 2, 3, 4]
```

Use lists when you need an ordered collection that can be changed.

---

## 🧱 **2. Tuple**

A **tuple** is similar to a list, but **immutable** — once created, it cannot be changed.

- Defined using parentheses `()`
- More memory-efficient than lists
- Often used for fixed data

Example:

```py
point = (10, 20)
person = ("Sam", 25)
```

Use tuples for data that should remain constant.

---

## 🔑 **3. Dictionary (dict)**

A **dictionary** stores data in **key-value pairs**.

- Defined using curly braces `{}`
- Keys must be unique
- Values can be any data type
- Great for structured data

Example:

```py
user = {
    "name": "Alice",
    "age": 30,
    "is_admin": True
}
```

Use dictionaries whenever you want to label your data with meaningful keys.

---

## 🧮 **4. Set**

A **set** is an unordered collection of **unique** items.

- Defined using `{}` or `set()`
- Automatically removes duplicates
- Useful for membership checks and mathematical operations

Example:

```py
unique_numbers = {1, 2, 3, 3, 4}
# Becomes: {1, 2, 3, 4}
```

Use sets when you need fast lookups or want to eliminate duplicates.

---

## 🧪 **Quick Example Using All Types**

```py
# List
colors = ["red", "blue", "green"]

# Tuple
dimensions = (1920, 1080)

# Dictionary
student = {"name": "Sam", "grade": "A"}

# Set
unique_ids = {101, 102, 103, 103}
```

---

## 📌 Summary Table

| Data Type      | Ordered                  | Mutable | Allows Duplicates | Example            |
| -------------- | ------------------------ | ------- | ----------------- | ------------------ |
| **List**       | Yes                      | Yes     | Yes               | `["a", "b"]`       |
| **Tuple**      | Yes                      | No      | Yes               | `(1, 2)`           |
| **Dictionary** | Keys: No order guarantee | Yes     | Keys unique       | `{"key": "value"}` |
| **Set**        | No                       | Yes     | No                | `{1, 2, 3}`        |

---

## 🎯 When to Use Each

- **List** → flexible, ordered data
- **Tuple** → fixed, unchangeable data
- **Set** → unique items, fast membership tests
- **Dictionary** → structured data with keys

These complex data types form the backbone of Python programming and will be used throughout the course.

---
