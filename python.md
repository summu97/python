What is Python?
--
* Python is a popular programming language.

It is used for:
--
* web development (server-side),
* software development,
* mathematics,
* system scripting.

What can Python do?
--
* Python can be used on a server to create web applications.
* Python can be used alongside software to create workflows.
* Python can connect to database systems. It can also read and modify files.
* Python can be used to handle big data and perform complex mathematics.

Why Python?
--
* Works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc).
* Simple syntax similar to the English language.
* Runs on an interpreter system, meaning that code can be executed as soon as it is written. This means that prototyping can be very quick.

The most recent major version of Python:
--
* Python 3

Python Versions:
--
* Python 1.0V introduced in Jan 1994
* Python 2.0V introduced in October 2000
* Python 3.0V introduced in December 2008

Python Syntax:
--
Example:
--
* print("Hello, World!")

IDENTIFIERS:
--
* A Name in Python Program is called Identifier.
* It can be Class Name OR Function Name OR Module Name OR Variable Name.
* a = 10

Rules to define Identifiers in Python:
--
* The only allowed characters in Python are:
  * alphabet symbols(either lower case or upper case)
  * digits(0 to 9)
  * underscore symbol(_)

* Identifier should not starts with digit:
  * total123 √
 
* Identifiers are case sensitive. Of course Python language is case sensitive language:
  * total=10
  * TOTAL=999
  * print(total) #10
  * print(TOTAL) #999

Identifier:
--
1) Alphabet Symbols (Either Upper case OR Lower case)
2) If Identifier is start with Underscore (_) then it indicates it is private.
3) Identifier should not start with Digits.
4) Identifiers are case sensitive.
5) We cannot use reserved words as identifiers
 Eg: def = 10 
6) There is no length limit for Python identifiers. But not recommended to use too 
lengthy identifiers.
7) Dollor ($) Symbol is not allowed in Python.

Note:
--
1) If identifier starts with _ symbol then it indicates that it is private
2) If identifier starts with __(Two Under Score Symbols) indicating that strongly private 
identifier.
3) If the identifier starts and ends with two underscore symbols then the identifier is 
language defined special name, which is also known as magic methods.
4) Eg: __add__

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

To get the list of key words:
--
* import keyword
* keyword.kwlist
['False', 'None', 'True', 'and', 'as', 'assert', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 
'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 
'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']

Note:
--
* Only True, False, None start with capital letter.

DATA TYPES:
--
* Data Type represents the type of data present inside a variable.
* In Python we are not required to specify the type explicitly. Based on value provided, the type will be assigned automatically.Hence Python is dynamically Typed Language.

Python contains the following inbuilt data types:
--
1) Int
2) Float
3) Complex
4) Bool
5) Str
6) Bytes
7) Bytearray
8) Range
9) List
10) Tuple
11) Set
12) Frozenset
13) Dict
14) None

Note: Python contains several inbuilt functions.
--
* type(): to check the type of variable
* id(): to get address of object
* print(): to print the value
* In Python everything is an Object.



