## Python Introduction

* Python is a powerful and beginner-friendly programming language created by Guido van Rossum in 1989 and officially released in 1991. 
* Guido developed Python during his free time over the holidays while working at a research institute in the Netherlands. 
* The name "Python" doesn't come from the snake but from Guido's favorite comedy show, "Monty Python's Flying Circus". 
* He wanted the language to be fun and easy to use, just like the show.

## Version :
* Python became popular because of its simple and readable syntax, which looks a lot like regular English. 
* Over time, it has evolved through various versions. The first version, Python 1.0, was released with basic features like functions and exception handling. 
* In 2000, Python 2.0 introduced advanced tools like list comprehensions and automatic memory cleanup. 
* Later, in 2008, Python 3.0 made the language cleaner and more efficient, though it wasn’t backward-compatible with older versions. 
* Today, Python is one of the most widely used programming languages in the world

## Applications of Python:
* Python is incredibly versatile and is used in many fields. 
* It is popular for web development, where frameworks like Django and Flask help build websites. 
* In data science and machine learning, Python is the top choice, with powerful libraries like Pandas and TensorFlow. 
* It is also used for automation, helping to write scripts that can save time by performing repetitive tasks automatically. 
* Python is even used in game development, desktop applications, and IoT (Internet of Things), making it a tool that fits almost every need.

## IDE Tools to use Python:
* IDE is Integrated Development Environment.
* It is a software application that provides tools like a code editor, debugger, and compiler/interpreter in one interface, making programming easier and more efficient.

## Python IDE Tools:
* PyCharm
* Visual Studio Code (VS Code)
* Jupyter Notebook
* IDLE
* Thonny
* Spyder
* Atom
* Sublime Text
* Anaconda
* Wing IDE

## Python Scripting
* Python scripting refers to writing Python code that automates tasks, processes data, or performs specific actions. 
* Unlike full-fledged software development, scripting focuses on creating scripts—short programs meant to execute a series of instructions or automate a task efficiently.

## Common Applications of Python Scripting
* System Administration:
Automating file operations, running system commands, or managing servers.
Example: Renaming multiple files in a folder.
* Data Processing:
Cleaning, transforming, and analyzing data.
Example: Reading CSV files, applying calculations, and saving results.
* Web Scraping:
Extracting data from websites.
Example: Scraping product prices from e-commerce sites.
* API Interaction:
Automating API calls for data retrieval or updates.
Example: Fetching weather data from an API.
* Testing and Debugging:
Writing test cases for software and debugging issues.
* Task Automation:
Scheduling and running periodic tasks.
Example: Sending automated email reminders.
* Machine Learning and AI:
Running training scripts for models.
Example: Automating data preprocessing and model evaluation.

## Python Interactive Mode (REPL)

* R: Read – It reads the code or input you type.
* E: Evaluate – It evaluates the code or expression.
* P: Print – It displays the result of the evaluation.
* L: Loop – It goes back to accept more input in a loop.

use windows powershell: code to check python version
## python --version
## numeric calculations

## variables
Variable are the containers which holds the data.

## ways of writting variables:
1. snake case : This is the most commonly used convention in Python. Words are separated by underscores, and all letters are lowercase.
Ex: my_variable_name = 10 
    first_name = "Eshwari"
	
2. Camel Case: This is less common in Python but still used by some developers. The first word is lowercase, and each subsequent word starts with an uppercase letter.
Ex: myVariableName = 10 
    firstName = "Eshwari"
	
3. Pascal Case: Similar to camel case, but the first word also starts with an uppercase letter. This is usually used for class names rather than variables.
Ex: MyVariableName = 10 
    FirstName = "Eshwari"

4. Upper Case (Screaming Snake Case):
Ex: MY_VARIABLE_NAME = "Esh" 
    USER_AGE = 45
	
5. Global vs Local Variables
A global variable is a variable that is declared outside of any function, class, or method and can be accessed and modified from anywhere in the program.
A local variable, on the other hand, is a variable that is declared within a function or block of code and is only accessible within that function or block.

Variable = 10 #global variable

Ex: 

    def function():

       value=5 #local variable
	   Global variable # using the global variable
	   variable += value
	   print(f"local variable:{value}")
	   print(f"global variable: {variable}")
	function()

## Rules for Naming Variables:
* Start with a Letter or Underscore
* Followed by Letters, Digits, or Underscores
* Case-Sensitive
* No Spaces
* No Reserved Keywords

## Data type
## Primitive Data Types:
Primitive data types are the most basic data types available within a programming language. These types are predefined by the language and are used to represent simple values.

* Integer (int): Represents whole numbers without a fractional part.
* Floating-point (float): Represents numbers with a fractional part (decimals).
* Character (char): Represents a single character (e.g., 'a', 'b', '1', '$').
* Boolean (bool): Represents true or false values (True or False in Python)

In Python, these include:
* int: For integers.
* float: For floating-point numbers.
* bool: For boolean values.
* str: For strings (though in some languages, str is not considered a primitive type).

## Non-Primitive Data Types:
Non-primitive data types are more complex and are derived from primitive data types. They are used to store multiple values or collections of values.

In Python, non-primitive data types include:

* list: Ordered and mutable sequences of elements.
* tuple: Ordered and immutable sequences of elements.
* set: Unordered and mutable collections of unique elements.
* frozenset: Unordered and immutable collections of unique elements.
* dict: Collections of key-value pairs.

## Comment Lines in Python
Comment lines are lines of text in a code file that the Python interpreter ignores. They are used to explain and annotate the code, making it more understandable for anyone reading it, including your future self.

## Why Use Comments?
* Clarify Code Functionality: Explain what specific parts of the code are doing.
* Provide Context: Offer background information or the purpose of certain sections of the code.
* Improve Readability: Make the code more readable and easier to follow.
* Debugging: Temporarily disable certain parts of the code without deleting them.

## Types of Comments in Python

* Single-line Comments = # 

* Multi-line comments = """ or ''' 

## Arithmetic Operators in Python:
* Addition (+) : Adds two operands.
a=1

b=2

result = a+b

print(result)

* Subtraction (-) : Subtracts the second operand from the first.
a=1

b=2

result = a-b

print(result)

* Multiplication (*) : Multiplies two operands

a=1

b=2

result = a*b

print(result)

* Division (/) : Divides the first operand by the second and returns a float.

a=1

b=2

result = a/b

print(result)

* Floor Division (//) : Divides the first operand by the second and returns the largest integer less than or equal to the result.

a=1

b=2

result = a//b

print(result)

* Modulus (%) : Returns the remainder of the division of the first operand by the second.

a=1

b=2

result = a%b

print(result)

* Exponentiation (**) : Raises the first operand to the power of the second.

a=1

b=2

result = a**b

print(result)

## Logical Functions in Python

* Logical AND (and): Returns True if both operands are true.
 a = True

b = False

result = a and b  # result is False

* Logical OR (or): Returns True if at least one of the operands is true.
a = True 

b = False 

result = a or b

* Logical NOT (not): Returns True if the operand is false and vice versa.

a = True 

result = not a # result is False



