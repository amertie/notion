# Python

Python is a popular programming language. It was created by Guido van Rossum, and released in 1991.

It is used for:

- web development (server-side),
- software development,
- mathematics,
- system scripting.

# What can Python do?

- Python can be used on a server to create web applications.
- Python can be used alongside software to create workflows.
- Python can connect to database systems. It can also read and modify files.
- Python can be used to handle big data and perform complex mathematics.
- Python can be used for rapid prototyping, or for production-ready software development.

# Why Python?

- Python works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc).
- Python has a simple syntax similar to the English language.
- Python has syntax that allows developers to write programs with fewer lines than some other programming languages.
- Python runs on an interpreter system, meaning that code can be executed as soon as it is written. This means that prototyping can be very quick.
- Python can be treated in a procedural way, an object-oriented way or a functional way.

# Good to know

- The most recent major version of Python is Python 3, which we shall be using in this tutorial. However, Python 2, although not being updated with anything other than security updates, is still quite popular.
- In this tutorial Python will be written in a text editor. It is possible to write Python in an Integrated Development Environment, such as Thonny, Pycharm, Netbeans or Eclipse which are particularly useful when managing larger collections of Python files.

# Python Syntax compared to other programming languages

- Python was designed for readability, and has some similarities to the English language with influence from mathematics.
- Python uses new lines to complete a command, as opposed to other programming languages which often use semicolons or parentheses.
- Python relies on indentation, using whitespace, to define scope; such as the scope of loops, functions and classes. Other programming languages often use curly-brackets for this purpose.

### Execute Python Syntax

As we learned in the previous page, Python syntax can be executed by writing directly in the Command Line:

>>> print("Hello, World!")Hello, World!

## On this page

---

Or by creating a python file on the server, using the .py file extension, and running it in the Command Line:

C:\Users\*Your Name*>python myfile.py

---

# Python Indentation

Indentation refers to the spaces at the beginning of a code line.

Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important.

Python uses indentation to indicate a block of code.

# Example

if 5 > 2:  print("Five is greater than two!")

Python will give you an error if you skip the indentation:

# Example

Syntax Error:

if 5 > 2:print("Five is greater than two!")

The number of spaces is up to you as a programmer, the most common use is four, but it has to be at least one.

# Example

if 5 > 2: print("Five is greater than two!") if 5 > 2:        print("Five is greater than two!")

You have to use the same number of spaces in the same block of code, otherwise Python will give you an error:

# Example

Syntax Error:

if 5 > 2: print("Five is greater than two!")        print("Five is greater than two!")

# Python Variables

In Python, variables are created when you assign a value to it:

# Example

Variables in Python:

x = 5y = "Hello, World!"

# Python Data Types

### Built-in Data Types

In programming, data type is an important concept.

Variables can store data of different types, and different types can do different things.

Python has the following data types built-in by default, in these categories:

| Text Type: | str |
| --- | --- |
| Numeric Types: | int, float, complex |
| Sequence Types: | list, tuple, range |
| Mapping Type: | dict |
| Set Types: | set, frozenset |
| Boolean Type: | bool |
| Binary Types: | bytes, bytearray, memoryview |
| None Type: | NoneType |

---

# Getting the Data Type

You can get the data type of any object by using the `type()` function:

# Example

Print the data type of the variable x:

x = 5print(type(x))

# Python Variables

# Variables

Variables are containers for storing data values.

# Creating Variables

Python has no command for declaring a variable.

A variable is created the moment you first assign a value to it.

# Example

x = 5y = "John"print(x)print(y)

Variables do not need to be declared with any particular *type*, and can even change type after they have been set.

# Example

x = 4       # x is of type intx = "Sally" # x is now of type strprint(x)

# Casting

If you want to specify the data type of a variable, this can be done with casting.

# Example

x = str(3)    # x will be '3'y = int(3)    # y will be 3z = float(3)  # z will be 3.0

# Get the Type

You can get the data type of a variable with the `type()` function.

# Example

x = 5y = "John"print(type(x))print(type(y))

You will learn more about [data types](https://www.w3schools.com/python/python_datatypes.asp) and [casting](https://www.w3schools.com/python/python_casting.asp) later in this tutorial.

# Single or Double Quotes?

String variables can be declared either by using single or double quotes:

# Case-Sensitive

Variable names are case-sensitive.

# Example

This will create two variables:

a = 4A = "Sally"#A will not overwrite a

# Python If ... Else

# Python Conditions and If statements

Python supports the usual logical conditions from mathematics:

- Equals: a == b
- Not Equals: a != b
- Less than: a < b
- Less than or equal to: a <= b
- Greater than: a > b
- Greater than or equal to: a >= b

These conditions can be used in several ways, most commonly in "if statements" and loops.

An "if statement" is written by using the if keyword.

# Example

If statement:

a = 33b = 200if b > a:  print("b is greater than a")

In this example we use two variables, a and b, which are used as part of the if statement to test whether b is greater than a. As a is 33, and b is 200, we know that 200 is greater than 33, and so we print to screen that "b is greater than a".

# Python Lists

---

mylist = ["apple", "banana", "cherry"]

---

# List

Lists are used to store multiple items in a single variable.

Lists are one of 4 built-in data types in Python used to store collections of data, the other 3 are [Tuple](https://www.w3schools.com/python/python_tuples.asp), [Set](https://www.w3schools.com/python/python_sets.asp), and [Dictionary](https://www.w3schools.com/python/python_dictionaries.asp), all with different qualities and usage.

Lists are created using square brackets:

# Example

Create a List:

thislist = ["apple", "banana", "cherry"]print(thislist)

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_list)

---

# List Items

List items are ordered, changeable, and allow duplicate values.

List items are indexed, the first item has index `[0]`, the second item has index `[1]` etc.

---

# Ordered

When we say that lists are ordered, it means that the items have a defined order, and that order will not change.

If you add new items to a list, the new items will be placed at the end of the list.

**Note:** There are some [list methods](https://www.w3schools.com/python/python_lists_methods.asp) that will change the order, but in general: the order of the items will not change.

---

# Changeable

The list is changeable, meaning that we can change, add, and remove items in a list after it has been created.

---

# Allow Duplicates

Since lists are indexed, lists can have items with the same value:

# Example

Lists allow duplicate values:

thislist = ["apple", "banana", "cherry", "apple", "cherry"]print(thislist)

[Try it Yourself »](https://www.w3schools.com/python/trypython.asp?filename=demo_list_duplicates)

---

---

# List Length

To determine how many items a list has, use the `len()` function:

# Example

Print the number of items in the list:

thislist = ["apple", "banana", "cherry"]print(len(thislist))

# List Items - Data Types

List items can be of any data type:

# Example

String, int and boolean data types:

list1 = ["apple", "banana", "cherry"]list2 = [1, 5, 7, 9, 3]list3 = [True, False, False]

A list can contain different data types:

# Example

A list with strings, integers and boolean values:

list1 = ["abc", 34, True, 40, "male"]

# type()

From Python's perspective, lists are defined as objects with the data type 'list':

<class 'list'>

# Example

What is the data type of a list?

mylist = ["apple", "banana", "cherry"]print(type(mylist))

# The list() Constructor

It is also possible to use the list() constructor when creating a new list.

# Example

Using the `list()` constructor to make a List:

thislist = list(("apple", "banana", "cherry")) # note the double round-bracketsprint(thislist)

# Python Collections (Arrays)

There are four collection data types in the Python programming language:

- **List** is a collection which is ordered and changeable. Allows duplicate members.
- **[Tuple](https://www.w3schools.com/python/python_tuples.asp)** is a collection which is ordered and unchangeable. Allows duplicate members.
- **[Set](https://www.w3schools.com/python/python_sets.asp)** is a collection which is unordered, unchangeable*, and unindexed. No duplicate members.
- **[Dictionary](https://www.w3schools.com/python/python_dictionaries.asp)** is a collection which is ordered** and changeable. No duplicate members.
- Set *items* are unchangeable, but you can remove and/or add items whenever you like.
- *As of Python version 3.7, dictionaries are *ordered*. In Python 3.6 and earlier, dictionaries are *unordered*.

When choosing a collection type, it is useful to understand the properties of that type. Choosing the right type for a particular data set could mean retention of meaning, and, it could mean an increase in efficiency or security.

---

![https://www.w3schools.com/images/colorpicker2000.png](https://www.w3schools.com/images/colorpicker2000.png)