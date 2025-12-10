# **Running `.py` Scripts vs Interactive REPL**

Python code can be executed in two main ways:

1. **Interactive mode (REPL)** — for quick tests and experimenting
2. **Script mode** — for writing full programs in `.py` files

Both are essential tools for learning and developing in Python.

---

## 🧪 **1. Interactive Mode (REPL)**

**REPL** stands for:
**R**ead → **E**valuate → **P**rint → **L**oop

It lets you run Python commands **one line at a time**, making it perfect for:

- Testing small pieces of code
- Trying out functions
- Exploring ideas quickly
- Learning Python basics

---

### ✔ How to Start the REPL

Open your terminal and type:

```bash
python
```

or:

```bash
python3
```

You should see something like:

```
>>> 
```

This is the Python prompt.

---

### ✔ Example (Interactive Mode)

```py
>>> 2 + 3
5
>>> print("Hello!")
Hello!
>>> name = "Sam"
>>> name
'Sam'
```

Exit the REPL with:

```py
exit()
```

or `Ctrl + D` (Linux/macOS) or `Ctrl + Z` + Enter (Windows).

---

## 📄 **2. Script Mode (`.py` Files)**

Script mode is used to write **complete programs** inside files ending with `.py`.

This mode is ideal for:

- Larger code projects
- Logic that spans multiple lines
- Programs you want to save and reuse
- Projects that grow over time

---

### ✔ Example Script

Create a file named:

```
hello.py
```

Write:

```py
print("Hello from a Python script!")
```

---

### ✔ Running the Script

Open your terminal in the same folder and run:

```bash
python hello.py
```

or:

```bash
python3 hello.py
```

Output:

```
Hello from a Python script!
```

---

## 🔍 **Key Differences**

| Feature         | REPL (Interactive Mode) | Script Mode (`.py` file)     |
| --------------- | ----------------------- | ---------------------------- |
| **Purpose**     | Quick testing, learning | Full programs, reusable code |
| **Execution**   | Line by line            | Entire file runs at once     |
| **Saves Code?** | No                      | Yes                          |
| **Best For**    | Trying ideas            | Building applications        |

---

## 🎯 **When to Use Which?**

### Use **REPL** when:

- You're experimenting
- You want instant feedback
- You're learning Python basics

### Use **`.py` scripts** when:

- Writing projects
- Saving work
- Building real programs
- Working with multiple files

---

## 🎉 Summary

Python gives you two powerful ways to run code:

* **Interactive REPL** → fast, simple, and great for testing
* **Script mode** → structured, reusable, and used in real development

Both are essential tools in your Python journey.

---
