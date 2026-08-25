# Python Method Overloading Example

A simple Python program demonstrating how method definitions with the same name behave in a class.

## 📌 Description

This project contains a Python class `A` with two `add()` methods.

In Python, traditional method overloading is **not supported**. When two methods have the same name, the latest method definition replaces the previous one.

Therefore, only the `add()` method accepting three parameters is available when the program runs.

## 💻 Code

```python
class A:
    def add(self, num1, num2):
        return num1 + num2

    def add(self, num1, num2, num3):
        return num1 + num2 + num3


obj = A()

print(obj.add(10, 20, 30))
```

## 🖥️ Output

```text
60
```

## 🧠 Key Concept

Python does not support traditional method overloading like Java or C++.

In this example:

```python
def add(self, num1, num2):
```

is replaced by:

```python
def add(self, num1, num2, num3):
```

So the program uses the second `add()` method.

## 🛠️ Technologies Used

* Python 3

## ▶️ How to Run

1. Install Python 3.
2. Clone this repository.
3. Open the project folder in VS Code or a terminal.
4. Run:

```bash
python main.py
```

## 📚 Learning Outcome

This example helps understand:

* Python classes and objects
* Methods
* Method overriding within the same class name
* Python's limitation regarding traditional method overloading

## 👨‍💻 Author

**Kotapati Dhananjay**
