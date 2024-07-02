Python is a high-level, interpreted programming language known for its simplicity and readability. Some of its key features include being easy to learn and use, having an extensive library and it is an interpreted language. Python is usually used for web development, data analysis, and machine learning.

To install in Windows

Download the Python installer from the official Python website (https://www.python.org/).

Run the installer and check "Add Python to PATH".

Follow the prompts to complete the installation.

For MacOS

Open Terminal.
Install Homebrew if not already installed, in Bash run /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
Then run "brew install python"
In Linux

Open Terminal.
Install Python using the package manager by running the following in bash sudo apt update sudo apt install python3
To verify if your machine has python, run the code "python --version" or "python3 --version". To set up your environment then run the following code python -m venv myenv source myenv/bin/activate # On Windows: myenv\Scripts\activate

To print "Hello World!" to the console, in Python write the code: print("Hello, World!") print is a built-in function that outputs text to the console and "Hello, World!" is a string

Basic data types used in Python are: Integer: Whole numbers (e.g., 2) Float: Numbers with a decimal point (e.g., 5.78) String: Text (e.g., "Good day!") Boolean: True or False values (True, False)

The usage of these data types in Python are as follows:

Integer
x = 6 print(x)

Float
y = 87.575 print(y)

String
z = "Python" print(z)

Boolean
is_math_boring = True print(is_math_boring)

Conditional statements are used to execute code based on a condition and loops are used to repeat a block of code multiple times. An example of an IF-Else code would be: age = 18 if age >= 18: print("You are an adult.") else: print("You are a minor.") For a loop it would be: for i in range(5): print(i)

Functions are reusable blocks of code that perform a specific task. They help to organize code and make it more readable and maintainable. A program for the required function: def add(x, y): return x + y

Calling the function
result = add(5, 3) print(result)

Lists are ordered collections of elements accessed by index while dictionaries are unordered collections of key-value pairs. Examples for each would be:
List
numbers = [2, 4, 6, 8, 10] print(numbers[0]) # Accessing the first element

Dictionary
person = {"name": "Othu", "age": 26} print(person["name"]) # Accessing value by key

Exception handling is a way to handle errors gracefully in a program. The try block contains code that might raise an exception. The except block catches and handles the exception. The finally block executes code regardless of whether an exception occurred. Example of them in action: try: result = 1 / 0 except ZeroDivisionError: print("Cannot divide by zero.") finally: print("Execution complete.")

Modules are files containing Python code (functions, classes, variables) that can be imported into other scripts and Packages are directories containing multiple modules. Required example: import math

result = math.sqrt(9) print(result)

Reading from a file: with open('fileName.txt', 'r') as file: content = file.read() print(content) Writing to a file: lines = ["Hello, World!", "Python is great!"] with open('output.txt', 'w') as file: for line in lines: file.write(line + '\n')
