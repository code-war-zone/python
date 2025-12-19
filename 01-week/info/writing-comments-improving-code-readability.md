# Writing Comments & Improving Code Readability

Readable code is easier to understand, maintain, and debug.
Writing clear comments and following good formatting practices helps both you and anyone else who works with your code.

---

## 📝 **1. Why Comments Matter**

Comments explain **what** your code does and **why** it does it.
They are ignored by Python during execution, but they improve clarity for humans.

Use comments to:

- Describe complex logic
- Explain the purpose of a function or value
- Make your code easier to revisit later

---

## 🟩 **2. Single-Line Comments**

Created using the `#` symbol.

```py
# This calculates the total price
total = price * quantity
```

Use single-line comments for short explanations.

---

## 🟦 **3. Multi-Line Comments (Documentation Strings)**

You can use triple quotes for longer descriptions, especially at the start of files or functions.

```py
"""
This program calculates the area of a rectangle.
User provides width and height.
"""
```

These are often called **docstrings** when used inside functions or modules.

---

## 📐 **4. Improving Code Readability**

Clean, readable code is just as important as correct code.

Here are simple best practices:

---

### ✔ Use Meaningful Variable Names

Bad:

```py
x = 10
```

Good:

```py
number_of_items = 10
```

---

### ✔ Use Consistent Formatting

Follow Python's standard style guide (PEP 8):

- Use **spaces**, not tabs
- One space around operators:

```py
total = price * quantity
```

- Blank lines to separate sections of code

---

### ✔ Keep Lines Short

Aim for lines under ~79 characters.

---

### ✔ Organize Code Into Logical Sections

Example:

```py
# Step 1: Get user input
width = float(input("Width: "))
height = float(input("Height: "))

# Step 2: Calculate area
area = width * height

# Step 3: Display result
print("Area:", area)
```

---

### ✔ Don’t Overuse Comments

Avoid comments that simply restate what the code already clearly shows.

Bad:

```py
# Add 1 to x
x = x + 1
```

Better:

```py
# Increment counter for next iteration
counter += 1
```

---

## 🎯 **5. Summary**

- Use comments to explain **why**, not obvious code.
- Follow PEP 8 for formatting and readability.
- Use meaningful variable names.
- Organize code into clear, logical sections.
- Write clean, readable code that others (and future you) can understand.

---
