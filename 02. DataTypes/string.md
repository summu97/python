MODIFY STRING:
--
Upper Case: The upper() method returns the string in upper case.
--
* EX: a = "Hello, World!"
print(a.upper())

--------------------------------------------------------------------
Lower Case: The lower() method returns the string in lower case
--
* EX: a = "Hello, World!"
print(a.lower())

--------------------------------------------------------------------
strip: To remove white spaces. Whitespace is the space before and/or after the actual text.
--
* EX: a = " Hello, World! "
print(a.strip()) # returns "Hello, World!"

--------------------------------------------------------------------
Replace String: The replace() method replaces a string with another string:
--
* EXa = "Hello, World!"
print(a.replace("H", "J"))
* This replaces "H" with "J".
--------------------------------------------------------------------
split: Converts string characters into list.
--
* Based on conditions we can split the string characters.
* EX: a = "Hello, World! hi world hi doooood"
b = a.split(",")
print(b)
print(a)
print(a.split("hi"))
--------------------------------------------------------------------
String Concatenation: To concatenate, or combine, two strings you can use the + operator.
--
* a = "Hello"
b = "World"
c = a + b
print(c)
* output: HelloWorld
  
* To add a space between them, add a " ":

a = "Hello"
b = "World"
c = a + " " + b
print(c)

--------------------------------------------------------------------
String Format: We cannot combine strings and nymbers.
--
* To combine F-String was introduced in Python 3.6, and is now the preferred way of formatting strings.
* To specify a string as an f-string, simply put an f in front of the string literal, and add curly brackets {} as placeholders for variables and other operations.
* EX: age = 36
txt = f"My name is John, I am {age}"
print(txt)
--------------------------------------------------------------------
