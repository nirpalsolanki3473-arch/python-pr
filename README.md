# Personal Data Collector (Python)

A simple interactive Python program that collects user information and demonstrates fundamental Python programming concepts such as variables, data types, type casting, arithmetic operations, memory addresses, and formatted output.

## 📌 Project Overview

This project is designed for Python beginners to practice:

* User input handling
* Variables and data types
* Type casting
* Arithmetic operations
* f-string formatting
* Using `type()` to inspect data types
* Using `id()` to view memory addresses
* Basic console output

The program asks the user for personal details and then displays processed information along with additional calculations.

---

## 🚀 Features

### User Information Collection

The program collects:

* Name
* Age
* Height (in meters)
* Favourite number

### Automatic Calculations

The program calculates:

* Approximate birth year
* Half of the user's age
* Double of the favourite number

### Python Concepts Demonstrated

#### Variables

Stores user information in variables.

#### Data Types

Uses:

* `str`
* `int`
* `float`

#### Type Casting

Converts user input strings into appropriate data types:

```python
age = int(input())
height = float(input())
number = int(input())
```

#### Arithmetic Operators

Examples:

```python
halfage = age / 2
n2 = number * 2
a = 2026 - age
```

#### Data Type Inspection

```python
type(age)
type(height)
```

#### Memory Address Inspection

```python
id(name)
id(age)
```

#### Formatted Strings (f-Strings)

```python
print(f"Name: {name}")
```

---

## 📂 Project Structure

```text
personal-data-collector/
│
├── main.py
└── README.md
```

---

## ▶️ How to Run

### Prerequisites

* Python 3.x installed

Check Python version:

```bash
python --version
```

### Run the Program

```bash
python main.py
```

or

```bash
python3 main.py
```

---

## 💻 Sample Output

```text
welcome to the interactive personal data collector

please enter your name : John
please enter your age : 20
please enter your height in meter : 1.75
enter your favourite number : 7

This program collects your personal information and demonstrates basic Python concepts like variables, data types, operators, and type casting.

thank you! here is information we collected :

name : John
age : 20
half age : 10.0
double favourite number : 14
height : 1.75
favourite number : 7

name type : <class 'str'>
age type : <class 'int'>
height type : <class 'float'>
number type : <class 'int'>

your birth year is approximately : 2006

thank you for using the personal Data collector!
Keep learning and exploring Python to improve your programming skills. Goodbye!
```

---

## 🎯 Learning Objectives

By completing this project, learners will understand:

* How to take user input
* How to convert input into different data types
* Basic mathematical operations in Python
* How Python stores objects in memory
* How to display dynamic information using f-strings
* How to create interactive command-line applications

---

## 🔧 Future Improvements

Possible enhancements:

* Add input validation
* Handle invalid age or height values
* Calculate exact birth year using the current date
* Store collected data in a file
* Add BMI calculation
* Create a graphical user interface (GUI)
* Export user information to CSV

---

## 🏷️ Technologies Used

* Python 3

---

## 📚 Concepts Covered

* Variables
* Strings
* Integers
* Floats
* User Input
* Type Casting
* Arithmetic Operators
* f-Strings
* `type()`
* `id()`
* Console Applications

---

## 👨‍💻 Author

Created as a beginner Python learning project to practice core programming fundamentals and interactive user input handling.

---

## ⭐ GitHub Topics

```text
python
python-project
beginner-project
cli-application
python-basics
learning-python
type-casting
user-input
```
