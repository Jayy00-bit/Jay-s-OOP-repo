# Using Special Methods in OOP 

This repository contains a Jupyter Notebook demonstrating how to use special (or "dunder") methods in Python's Object-Oriented Programming (OOP)[cite: 1]. It explains how to use these methods so custom objects can behave naturally and intuitively[cite: 1].

##  Topics Covered

This notebook explores the following special methods:

* **Initialization & Destruction:** 
  * `__init__()`: Used to initialize the attributes of an object upon creation[cite: 1].
  * `__del__()`: The destructor method, executed when an object is being removed from memory[cite: 1].
* **String Representation:** 
  * `__str__()`: Provides a human-readable (informal) string representation of an object[cite: 1].
  * `__repr__()`: Provides an official or developer-oriented representation[cite: 1].
* **Collection & Container Behavior:** 
  * `__len__()`: Allows custom objects to define their own length[cite: 1].
  * `__getitem__()`: Enables an object to behave like a sequence by allowing index access[cite: 1].
  * `__setitem__()`: Enables assignment using indexing notation[cite: 1].
  * `__contains__()`: Defines membership testing and determines how the `in` operator behaves[cite: 1].
* **Comparisons & Operators:** 
  * `__eq__()`: Defines how objects should be compared for equality[cite: 1].
  * `__add__()`, `__sub__()`, `__mul__()`: Operator overloading to define how standard math operators apply to custom objects[cite: 1].
* **Control Flow & Execution:** 
  * `__call__()`: Allows an object to be invoked and behave like a function[cite: 1].
  * `__iter__()` and `__next__()`: Provides iteration support to allow objects to work in loops[cite: 1].
  * `__bool__()`: Determines how an object behaves in Boolean contexts and controls truth-value testing[cite: 1].

##  Practical Examples

The notebook uses practical Python 3 code blocks to demonstrate these concepts[cite: 1]. Example implementations include:
* Basic classes like `Student`, `Book`, and `Vector`[cite: 1].
* Iterators like a `Counter` class[cite: 1].
* A culminating `ShoppingCart` challenge that combines multiple special methods (`__str__`, `__len__`, `__getitem__`, `__setitem__`, `__eq__`, and `__add__`) to manage a custom cart object[cite: 1].

## 🛠️ Built With
* Python 3[cite: 1]
* Jupyter Notebook[cite: 1]

## 💡 Usage

To run this notebook locally:
1. Clone this repository to your local machine.
2. Ensure you have Jupyter installed (e.g., via Anaconda or `pip install notebook`).
3. Open the `.ipynb` file in your Jupyter environment to run and modify the cells.