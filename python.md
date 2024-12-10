What is Python?
--
* Python is a popular programming language.

It is used for:
--
* web development (server-side),
* software development,
* mathematics,
* system scripting.

Why Python?
--
* Works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc).
* Simple syntax similar to the English language.
* Runs on an interpreter system, meaning that code can be executed as soon as it is written. This means that prototyping can be very quick.

The most recent major version of Python:
--
* Python 3

--------------------------------------------------------
Syntax: print("Hello World!")
--
--------------------------------------------------------
Comments:
--
* Single comment: # This is how a single comment is written.
* Multi line comment:
"""
This is 
how a multiline 
comment is written
"""

--------------------------------------------------------
IDENTIFIERS:
--
* A Name in Python Program is called Identifier.
* It can be Class Name OR Function Name OR Module Name OR Variable Name.
* a = 10

Note:
--
1) If identifier starts with _ symbol then it indicates that it is private
2) If identifier starts with __(Two Under Score Symbols) indicating that strongly private 
identifier.
3) If the identifier starts and ends with two underscore symbols then the identifier is 
language defined special name, which is also known as magic methods.
4) Eg: __add__
--------------------------------------------------------
Variables: Containers to store data.
--
* x = 5 # x is of type int
* y = "John" # y is now of type str

Variable Names: A variable can have a short name (like x and y) or a more descriptive name (age, carname, total_volume). Rules for Python variables:
--
* A variable name must start with a letter or the underscore character
* A variable name cannot start with a number
* A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
* Variable names are case-sensitive (age, Age and AGE are three different variables)
* A variable name cannot be any of the Python keywords.

Multi Words Variable Names: You can use any of below casing methods to describe multi line variable names.
--

* Camel Case: Each word, except the first, starts with a capital letter. EX: myVariableName = "John"
* Pascal Case: Each word starts with a capital letter. EX: MyVariableName = "John"
* Snake Case: Each word is separated by an underscore character. EX: my_variable_name = "John"

Assign Multiple Values:
--
* Many Values to Multiple Variables. EX: x, y, z = "Orange", "Banana", "Cherry"
  
Note: Make sure the number of variables matches the number of values, or else you will get an error.
--

* One Value to Multiple Variables. EX: x = y = z = "Orange"
* Unpack a Collection: If you have a collection of values in a list, tuple etc. Python allows you to extract the values into variables. This is called unpacking.

Example: Unpack a list:

fruits = ["apple", "banana", "cherry"]
x, y, z = fruits
print(x)
print(y)
print(z)

Global Variables: Variables that are created outside of a function (as in all of the examples in the previous pages) are known as global variables.
--
* Example: 
x = "awesome"

def myfunc():
  print("Python is " + x)

myfunc()

* Create a variable inside a function, with the same name as the global variable:

x = "awesome"

def myfunc():
  x = "fantastic"
  print("Python is " + x)

myfunc()

print("Python is " + x)
--------------------------------------------------------
The global Keyword: Normally, when you create a variable inside a function, that variable is local, and can only be used inside that function.
--
* If you use the global keyword, the variable belongs to the global scope:

def myfunc():
  global x
  x = "fantastic"

myfunc()

print("Python is " + x)

NOTE: You have global variables specified and want to over ride those variable values, then use "global" key word inside function.
--
* EX:
x = "awesome"

def myfunc():
  global x
  x = "fantastic"

myfunc()

print("Python is " + x)
--------------------------------------------------------
Casting: To convert one data type to another data type.
--
* x = str(3)    # x will be '3'
* y = int(3)    # y will be 3
* z = float(3)  # z will be 3.0
--------------------------------------------------------
Type function: To get the data type of variable.
--
y = "John"
print(type(y)) 
--------------------------------------------------------
Single or Double Quotes: You can choose any.
--
x = "John"
# is the same as
x = 'John'
--------------------------------------------------------
Data Types:
--

* Text Type:		str
* Numeric Types:	int, float, complex
* Sequence Types:	list, tuple, range
* Mapping Type:		dict
* Set Types:		set, frozenset
* Boolean Type:		bool
* Binary Types:		bytes, bytearray, memoryview
* None Type:		NoneType


Example	 					Data Type
x = "Hello World"				str	
x = 20						int	
x = 20.5					float	
x = 1j						complex	
x = ["apple", "banana", "cherry"]		list	
x = ("apple", "banana", "cherry")		tuple	
x = range(6)					range	
x = {"name" : "John", "age" : 36}		dict	
x = {"apple", "banana", "cherry"}		set	
x = frozenset({"apple", "banana", "cherry"})	frozenset	
x = True					bool	
x = b"Hello"					bytes	
x = bytearray(5)				bytearray	
x = memoryview(bytes(5))			memoryview	
x = None					NoneType

Setting the Specific Data Type: If you want to specify the data type, you can use the following constructor functions:
--
Example						Data Type
x = str("Hello World")				str	
x = int(20)					int	
x = float(20.5)					float	
x = complex(1j)					complex	
x = list(("apple", "banana", "cherry"))		list	
x = tuple(("apple", "banana", "cherry"))	tuple	
x = range(6)					range	
x = dict(name="John", age=36)			dict	
x = set(("apple", "banana", "cherry"))		set	
x = frozenset(("apple", "banana", "cherry"))	frozenset	
x = bool(5)					bool	
x = bytes(5)					bytes	
x = bytearray(5)				bytearray	
x = memoryview(bytes(5))			memoryview
--------------------------------------------------------
RESERVED WORDS:
--
* In Python some words are reserved to represent some meaning or functionality. Such types of words are called reserved words.
* There are 33 reserved words available in Python.
  * True, False, None
  * and, or ,not,is
  * if, elif, else
  * while, for, break, continue, return, in, yield
  * try, except, finally, raise, assert
  * import, from, as, class, def, pass, global, nonlocal, lambda, del, with
  
Note:
--
* Only True, False, None start with capital letter.

--------------------------------------------------------
Inbuilt functions.
--
* type(): to check the type of variable
* id(): to get address of object
* print(): to print the value
* In Python everything is an Object.
--------------------------------------------------------
