# 🐍 Python Class Notes – Complete Guide

> 📘 **These are full-length Python class notes rewritten for direct reading on GitHub.**  
> No need to download anything — just scroll and study 🚀

---

## 🔧 Python Installation & Version Check

- First, talk about Python installation.
- To check the Python version installed on your system:
```bash
python --version
```
- If Python is already installed, it will show the version.
- Otherwise, download Python from the official website.

---

## 👨‍💻 About Python

- Python was created by **Guido Van Rossum** in **1989** 🧠
- Current version of Python: **13.14**
- Python got its name from the comedy show 🎭 **Monty Python’s Circus**

---

## ▶️ Modes to Run Python Programs

### 1️⃣ Interpreter Mode
- Runs code line by line
- Used via **PowerShell / CMD**

### 2️⃣ Script Mode
- Runs a complete Python file
- Uses **IDLE (Integrated Development Learning Environment)**

### 📌 Important Commands

```bash
py -m idlelib
python example.py
```

- Python file extension: **.py**

---

## 🖥️ How to Open Python (IDLE)

1. Press **Windows Key**
2. Search **IDLE**
3. Open IDLE
4. Click **File → Open**
5. Navigate to your Python file

---

## 🖨️ print() Function in Python

### Syntax
```python
print("Hello")
```

### Key Points
- Default `end="\n"` (new line)
- Default `sep=" "` (space)
- `print()` alone gives a blank line

---

## 📦 Variables in Python

### Syntax
```python
x = 10
name = "Om"
```

### Definition
A variable is a container used to store data.

### Rules
- Must start with an alphabet
- No spaces allowed
- No special characters or numbers at start
- Cannot be a keyword

### Keywords
`if, else, elif, while, for, break`

---

## 🧬 Data Types in Python

### 🔹 Primitive Data Types

| Type | Description |
|----|------------|
| int | Integer values |
| float | Decimal numbers |
| str | Strings |
| bool | True / False |
| complex | Imaginary numbers |

### 🔹 Collection Data Types
- List
- Tuple
- Set
- Frozen Set
- Dictionary

---

## 📚 List

- Collection of multiple elements
- Can store different data types
- **Mutable**
- Denoted by `[]`

### Operations
- Indexing
- Slicing
- CRUD (Create, Read, Update, Delete)

```python
a = [1,2,3,4,5]
```

### Built-in Methods
`append(), insert(), extend(), remove(), pop(), index(), count(), sort(), reverse(), copy()`

---

## 📕 Tuple

- Collection of multiple elements
- **Immutable**
- Denoted by `()`

```python
a = (1,2,3,4,5)
```

### Operations
- Indexing
- Slicing
- Create
- Read
- Delete

### Methods
`count(), index()`

---

## 📘 Set

- Collection of **unique elements**
- **Mutable**
- No fixed indexing
- Random order
- Denoted by `{}`

```python
a = {1,2,3,4,5}
```

### Methods
`add(), update(), remove(), discard(), pop(), intersection(), union(), difference(), clear()`

---

## ❄️ Frozen Set

- Collection of unique elements
- **Immutable**
- Created using `frozenset()`

### Operations
- intersection()
- union()
- difference()
- isdisjoint()
- issubset()

---

## 📙 Dictionary

- Stores data as **key-value pairs**
- **Mutable**
- Keys must be unique

```python
a = {"name":"om","lastname":"vaja"}
```

### Operations
- Create
- Read
- Update
- Delete

### Methods
`get(), update(), setdefault(), keys(), values(), items(), pop(), clear()`

---

## 📂 List of Dictionaries

```python
students = [
 {"id":1,"name":"Alice","grade":"A"},
 {"id":2,"name":"Bob","grade":"B"},
 {"id":3,"name":"Charlie","grade":"C"}
]
```

### Operations
- Indexing
- Updating
- Inserting
- Deleting
- Slicing

---

## ➕ Operators in Python

### Types
- Arithmetic: `+ - * / % **`
- Comparison: `== != < > <= >=`
- Assignment: `= += -= *= /=`
- Logical: `and or not`
- Identity: `is is not`
- Membership: `in not in`

---

## 🔄 Type Casting

### Primitive Conversion
- int → float
- float → int
- str → bool
- bool → str

### Collection Conversion
- list ↔ tuple
- list ↔ set

---

## 🧮 Operator Precedence

1. `()`
2. `**`
3. `* / // %`
4. `+ -`
5. `=`

---

## 🔁 Control Structures & Loops

### Types
- Sequential
- Conditional
- Repetitional
- Jump Statements

### Conditional Statements
```python
if condition:
    pass
elif condition:
    pass
else:
    pass
```

---

## 🔂 Loops

### While Loop
```python
i = 1
while i <= 5:
    print(i)
    i += 1
```

### For Loop
```python
for i in range(1,6):
    print(i)
```

---

## ⛔ Jump Control Statements

- `break` → stops loop
- `continue` → skips iteration
- `pass` → placeholder

> ⚠️ while loop does not support continue

---

## 🎯 Match Case

- Used in menu-driven programs
- Alternative to if-elif

```python
match choice:
    case 1:
        print("One")
    case _:
        print("Invalid")
```

---

## 🧭 Flowchart & Algorithm

### Flowchart
- Pictorial representation of logic

### Algorithm
- Step-by-step procedure to solve a problem

---

## 🧠 Functions in Python

- Reusable block of code

### Types
- Built-in functions
- User Defined Functions (UDF)

```python
def add(a,b):
    return a+b
```

---

## 📝 Function Arguments

- Positional
- Arbitrary
- Keyword
- Default

---

## 📄 Docstring

- Used to document functions, classes, modules

```python
def func():
    """This is a docstring"""
```

### Access
- `__doc__`
- `help()`

---

## 🔁 Recursion

- Function calling itself until condition

---

## ⚡ Lambda Function

- Anonymous function
- Single-line expression

```python
lambda x,y: x+y
```

---

## 🌍 Global Keyword

- Used to access global variables inside local scope

---

## 📊 Arrays in Python

- Collection of same datatype elements
- Created using lists

### Types
- 1D Array
- Multi-Dimensional Array

### Operations
- Indexing
- Slicing
- CRUD

---

## 🎉 End of Python Notes

⭐ If this helped you, **give the repo a star**!
