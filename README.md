# Python Full Course - All Code

This repository contains all the code examples, assignments, and projects from the Python Full Course.

## Table of Contents

1. [Introduction](#introduction)
2. [Setting Up](#setting-up)
3. [Course Modules](#course-modules)
    - [Module 1: Python Basics](#module-1-python-basics)
    - [Module 2: Control Flow](#module-2-control-flow)
    - [Module 3: Functions](#module-3-functions)
    - [Module 4: Data Structures](#module-4-data-structures)
    - [Module 5: Object-Oriented Programming (OOP)](#module-5-object-oriented-programming-oop)
    - [Module 6: Modules and Packages](#module-6-modules-and-packages)
    - [Module 7: File Handling](#module-7-file-handling)
    - [Module 8: Error Handling](#module-8-error-handling)
    - [Module 9: Advanced Topics](#module-9-advanced-topics)
    - [Module 10: Final Project](#module-10-final-project)
4. [Contributing](#contributing)
5. [License](#license)

---

## Introduction

This course covers Python from basic to advanced levels, focusing on practical examples and coding challenges. Each module includes theory, code examples, and exercises.

## Setting Up

1. Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).
2. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/yourusername/python-full-course.git
    ```
3. Navigate to the course directory:
    ```bash
    cd python-full-course
    ```

## Course Modules

### Module 1: Python Basics

- **Topics Covered:**
    - Variables, Data Types
    - Basic Input/Output
    - Comments and Indentation
- **Code Example:**
    ```python
    # Example of basic variables and print statement
    name = "John"
    age = 25
    print(f"Hello, {name}. You are {age} years old.")
    ```

### Module 2: Control Flow

- **Topics Covered:**
    - `if`, `else`, and `elif` statements
    - Loops (`for`, `while`)
- **Code Example:**
    ```python
    # Example of control flow
    number = 10
    if number > 5:
        print("Number is greater than 5")
    else:
        print("Number is 5 or less")
    ```

### Module 3: Functions

- **Topics Covered:**
    - Defining functions
    - Parameters and Return Values
    - Lambda functions
- **Code Example:**
    ```python
    # Example of a function
    def greet(name):
        return f"Hello, {name}!"

    print(greet("Alice"))
    ```

### Module 4: Data Structures

- **Topics Covered:**
    - Lists, Tuples, Sets, and Dictionaries
    - List Comprehensions
- **Code Example:**
    ```python
    # Example of a list and dictionary
    fruits = ["apple", "banana", "cherry"]
    person = {"name": "Alice", "age": 30}
    
    print(fruits[0])  # Output: apple
    print(person["name"])  # Output: Alice
    ```

### Module 5: Object-Oriented Programming (OOP)

- **Topics Covered:**
    - Classes and Objects
    - Inheritance, Encapsulation, Polymorphism
- **Code Example:**
    ```python
    # Example of a class in Python
    class Dog:
        def __init__(self, name, age):
            self.name = name
            self.age = age

        def bark(self):
            return "Woof!"

    my_dog = Dog("Buddy", 5)
    print(my_dog.bark())  # Output: Woof!
    ```

### Module 6: Modules and Packages

- **Topics Covered:**
    - Importing Modules
    - Creating and Using Packages
- **Code Example:**
    ```python
    # Importing math module
    import math
    print(math.sqrt(16))  # Output: 4.0
    ```

### Module 7: File Handling

- **Topics Covered:**
    - Reading and Writing Files
    - Working with File Paths
- **Code Example:**
    ```python
    # Writing to a file
    with open("example.txt", "w") as file:
        file.write("Hello, World!")
    ```

### Module 8: Error Handling

- **Topics Covered:**
    - `try`, `except`, and `finally`
    - Raising Exceptions
- **Code Example:**
    ```python
    # Example of error handling
    try:
        number = int(input("Enter a number: "))
        print(f"You entered: {number}")
    except ValueError:
        print("That's not a valid number!")
    ```

### Module 9: Advanced Topics

- **Topics Covered:**
    - Decorators
    - Generators
    - Context Managers
- **Code Example:**
    ```python
    # Example of a generator
    def count_up_to(max):
        count = 1
        while count <= max:
            yield count
            count += 1

    for num in count_up_to(5):
        print(num)  # Output: 1, 2, 3, 4, 5
    ```

### Module 10: Final Project

- **Project:** 
    - Build a small Python application using all the concepts learned in the course. Examples: To-Do List, Calculator, or a Web Scraper.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
