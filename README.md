[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15319602&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

Python is a high-level, general-purpose programming language. It is an interpreted language, meaning that it does not need to be compiled before execution. Python has a simple and elegant syntax, which makes it easy to read and write. It also has a large standard library, which provides a wide range of functionality. Python has been vastly used in Web Development, Python-based frameworks such as Django and Flask allow developers to build dynamic and interactive websites and web applications.



2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   For windows;
   a. Visit the official Python website: https://www.python.org/downloads/
   b. Click on the "Download Python 3.x.x" button for your system architecture (32-bit or 64-bit).
   c. Run the downloaded executable file and follow the on-screen instructions.
   d. Make sure to select the "Add Python 3.x to PATH" option during installation.


3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   def main():
   print("Hello, World!")
   main(): This is the main function of the program. It is the starting point for execution.
   print("Hello, World!"): This is a print statement. It prints the text "Hello, World!" to the console.


4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

Integer (int): Whole numbers, both positive and negative.
Float (float): Decimal numbers with a fractional part.
String (str): Sequences of characters enclosed in single or double quotes.
Boolean (bool): True or False values.
NoneType (None): A special value that represents an empty non-existent value.

num=10 #int
dec-2.5 #int
name="Anne" #str
Is_raining=true #bool
nothing= None #nonetype

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

Conditional statements in Python control the flow of execution based on specified conditions. The most common conditional statement is the 'if-else' statement, which evaluates a condition and executes different blocks of code depending on the result. Loops in Python allow you to iterate over sequences of data and execute a block of code for each element. The most common loop type is the 'for' loop, which iterates over a range of values or a sequence of items.

Examples of if-else
if number > 0:
print("the number is positive")
else:
print("the number is not positive")

for
list1= [1,2,3,4,5]
for element in list1:
print(element)


6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

Functions in Python are blocks of code that perform a specific task and can be reused in multiple parts of a program. They help in structuring code, improving readability, and enhancing code reusability. They are useful in complex programs into smaller, manageable chunks, making code easier to understand and maintain.They can also be called multiple times, with different arguments, reducing the need for repetitive code.

def sum(a,b):
Args: a:The first number.
      b:The second number.

Returns:
 The sum of a and b


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

Lists are an ordered sequence of elements. They can contain any type of object, including other lists or dictionaries. Lists are mutable, meaning that you can add, remove, or change elements in the list.
Dictionaries are a collection of key-value pairs. The keys must be unique, and the values can be any type of object. Dictionaries are mutable, meaning that you can add, remove, or change key-value pairs in the dictionary.

Numbers=[1,2,3,4,5]
print(numbers)

Dictionary={"name":"Anne","age":28,"city":"nairobi"}
print(Dictionary)

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

   Exception handling is a mechanism in Python that allows you to control the flow of execution when an error occurs. It enables you to handle errors gracefully and provide a user-friendly response instead of abruptly terminating the program.

try:
    # Open a non-existent file
    file = open("my_file.txt", "r")
except FileNotFoundError:
    # Exception handling code for FileNotFoundError
    print("File not found. Please check the file path.")
finally:
    # Cleanup code
    # Close the file if it was successfully opened
    if file:
        file.close()


9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   Modules are individual Python files that contain related code and functions.They provide a way to organize and reuse code, making it more modular and maintainable eg .py extention. Packages are collections of related modules organized in a hierarchical directory structure. Packages typically contain an _init_.py files in each directory.

   import math

radius = 5
area = math.pi * radius**2
print(f"The area of the circle is: {area}")


10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.


file = open("example.txt", "r")
contents = file.read()
print(contents)
file.close()

file in write mode
file = open("example.txt", "w")
file.writelines(["Hello", "world!", "\n"])
file.close()


# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


