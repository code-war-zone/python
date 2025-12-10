# **Variables & Naming Conventions**

Variables are one of the core building blocks of programming.
They allow you to store information and use it throughout your program.

---

## 🧱 **What Is a Variable?**

A **variable** is a name that stores a value in memory.

Example:

```py
name = "Sam"
age = 25
```

Here:

-`name` → stores the string `"Sam"`
-`age` → stores the integer `25`

You can use these values later in your code.

---

## 🏷️ **Naming Variables**

Good variable names make your code easier to read and understand.

### ✔ Rules (Required)

Python has a few strict naming rules:

1. Must start with a **letter** or an **underscore (`_`)**
2. Cannot start with a **number**
3. Cannot contain **spaces**
4. Can only use **letters, numbers, and underscores**
5. Are **case-sensitive**

   * `age`, `Age`, and `AGE` are all different

Valid:

```py
first_name
counter
user_age
```

Invalid:

```py
2name
first-name
user age
```

---

## 🧹 **Naming Conventions (Best Practices)**

Python follows certain style conventions to keep code clean:

### ✔ Use `snake_case`

Words are lowercase and separated by underscores.

```py
total_price = 19.99
user_email = "test@example.com"
```

### ✔ Use descriptive names

Bad:

```py
x = 10
```

Good:

```py
number_of_students = 10
```

### ✔ Avoid single-letter names (except in loops)

Bad:

```py
n = 5
```

Better:

```py
num_items = 5
```

### ✔ Constants in UPPERCASE

Used for values that should not change.

```py
PI = 3.14
MAX_USERS = 50
```

---

## 🔁 **Assigning and Reassigning Variables**

Variables can change:

```py
score = 10
score = 20
```

You can also assign multiple variables at once:

```py
x, y = 5, 10
```

---

## 🧪 **Quick Practice**

Try writing variables for:

- Your name
- Your country
- Your age
- Your favorite number

Example:

```py
full_name = "Sarah"
age = 30
favorite_number = 7
```

---

## 🎉 Summary

* Variables store values you want to use later
* Follow Python’s naming rules and conventions
* Use descriptive, readable names
* Prefer snake_case for all variables

Clear variable names make your programs easier to understand and maintain.

---

