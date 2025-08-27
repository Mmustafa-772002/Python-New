# Python 

A python is high level obeject orinetd programming language.
python has dynamic semantics and high level built in data structures, rich library and easy to use syntax. 
which is invented by guido van rossum in 1991.

## Features of Python
- Easy to learn and use
- Free and open source
- Portable 
- Interpreted language
- Object oriented language
- Extensible
- Large standard library
- GUI Programming support
- Integrated
- Dynamically typed language

## Applications of Python
- Web Development
- Game Development
- Desktop GUI Applications
- Scientific and Numeric Applications
- Software Development
- Business Applications
- Network Programming

## Python Installation
- Download the latest version of python from [python.org](https://www.python.org/downloads/)
- Follow the instructions to install python on your system
- Verify the installation by opening a terminal and typing `python --version` or `python3 --version`
- You can also use package managers like `apt`, `brew`, `choco` to install python
- For Windows, you can download the installer from [python.org](https://www.python.org/downloads/windows/)
- For macOS, you can use `brew install python`
- For Linux, you can use `apt-get install python3` or `yum install python
- You can also use Anaconda distribution for scientific computing and data science

## Running Python Code
- You can run python code in interactive mode by typing `python` or `python3` in the terminal
- You can run python code from a file by typing `python filename.py` or `python
3 filename.py` in the terminal
- You can use IDEs like PyCharm, VSCode, Jupyter Notebook, etc. to write and run python code
- You can also use online platforms like Repl.it, Google Colab, etc. to write and run python code

## Python Syntax
- Python uses indentation to define blocks of code
- Python uses `#` for single line comments and `'''` or `"""` for multi-line comments

- Start with a simple "Hello, World!" program:
```python   
print("Hello, World!")
```
pip and module in python
- pip is a package manager for python that allows you to install and manage additional libraries and dependencies

- You can install a package using the command `pip install package_name` or `pip3 install package_name`
- You can uninstall a package using the command `pip uninstall package_name` or `pip3 uninstall package_name`
- You can list all installed packages using the command `pip list` or `pip3 list
- You can upgrade a package using the command `pip install --upgrade package_name` or `pip3 install --upgrade package_name`
- A module is a file containing python code that can define functions, classes, and variables
- You can import a module using the `import` statement
```python
import math
print(math.sqrt(16))
```
- You can import specific functions or variables from a module using the `from` keyword
```python
from math import sqrt
print(sqrt(16))
```
- You can create your own module by saving your python code in a `.py` file and importing it in another python file
```python
# mymodule.py
def greet(name):
    return f"Hello, {name}!"    
# main.py
from mymodule import greet
print(greet("Alice"))
```

## Python Data Types
- Python has several built-in data types including:
- Numeric types: int, float, complex
- Sequence types: list, tuple, range
- Text type: str
- Set types: set, frozenset
- Mapping type: dict
- Boolean type: bool
- None type: NoneType
- You can check the type of a variable using the `type()` function
```python
x = 5
print(type(x))  # Output: <class 'int'>
y = 3.14
print(type(y))  # Output: <class 'float'>
z = "Hello"
print(type(z))  # Output: <class 'str'>
a = [1, 2, 3]
print(type(a))  # Output: <class 'list'>
b = (1, 2, 3)
print(type(b))  # Output: <class 'tuple'>
c = {1, 2, 3}
print(type(c))  # Output: <class 'set'>
d = {'a': 1, 'b': 2}
print(type(d))  # Output: <class 'dict'>
e = True
print(type(e))  # Output: <class 'bool'>
f = None
print(type(f))  # Output: <class 'NoneType'>
```
- You can convert between data types using built-in functions like `int()`, `float()`, `str()`, `list()`, `tuple()`, `set()`, `dict()`, etc.
```python

x = 5
y = float(x)
print(y)  # Output: 5.0
z = str(x)
print(z)  # Output: "5"
a = [1, 2, 3]
b = tuple(a)
print(b)  # Output: (1, 2, 3)
c = set(a)
print(c)  # Output: {1, 2, 3}
d = {'a': 1, 'b': 2}
e = list(d.keys())
print(e)  # Output: ['a', 'b']
f = list(d.values())
print(f)  # Output: [1, 2]
g = list(d.items())
print(g)  # Output: [('a', 1), ('b', 2)]
```

- Python also supports type hinting to indicate the expected data type of a variable or function parameter
```python
def greet(name: str) -> str:
    return f"Hello, {name}!"
print(greet("Alice"))  # Output: "Hello, Alice!"
```
Rules for naming variables in python
- Variable names must start with a letter (a-z, A-Z) or an underscore (_)
- Variable names can contain letters, digits (0-9), and underscores (_)
- Variable names are case-sensitive (e.g., `myVar` and `myvar` are different variables)
- Variable names cannot be a reserved keyword in python (e.g., `if`, `else
, `while`, `for`, `def`, `class`, etc.)
- Variable names should be descriptive and meaningful
- Variable names should not start with a digit
- Variable names should not contain special characters (e.g., `!`, `@`, `#`, `$`, `%`, `^`, `&`, `*`, `(`, `)`, `-`, `+`, `=`, `{`, `}`, `[`, `]`, `|`, `\`, `:`, `;`, `"`, `'`, `<`, `>`, `,`, `.`, `?`, `/`)
- Variable names should not be too long or too short
- Use snake_case for variable names (e.g., `my_variable_name`)
- Avoid using single character variable names (e.g., `x`, `y`, `z`) unless they are used in a very small scope (e.g., in a loop)
- Avoid using names that are too similar to built-in functions or types (e.g., `list`, `str`, `int`, `float`, etc.)
- Use meaningful names that convey the purpose of the variable (e.g., `total_price`, `user_name`, `is_valid`, etc.)
- Use consistent naming conventions throughout your codebase
- Use comments to explain the purpose of the variable if it is not clear from the name
```python
# Good variable names
user_name = "Alice"
total_price = 100.50
is_valid = True
# Bad variable names
x = "Alice"
y = 100.50
z = True
list = [1, 2, 3]
str = "Hello"
int = 5
float = 3.14
def = "function"
class = "MyClass"
# Reserved keywords
if = True
else = False
while = True
for = 10
def = "function"
class = "MyClass"
try = "try"
except = "except"
finally = "finally" 
with = "with"
lambda = "lambda"
import = "import"

# Example of valid variable names
my_variable = 10
_variable2 = 20
variable_3 = 30
variableName = 40
variable_name_with_underscores = 50
variableNameWithCamelCase = 60
variable_name_with_numbers_123 = 70
variable_name_with_special_characters_ = 80

# Example of invalid variable names
2variable = 10  # starts with a digit
my-variable = 20  # contains a hyphen
my variable = 30  # contains a space
my@variable = 40  # contains a special character
my.variable = 50  # contains a dot
my,variable = 60  # contains a comma
my;variable = 70  # contains a semicolon
my:variable = 80  # contains a colon
```
