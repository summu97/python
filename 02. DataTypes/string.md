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
String Formatting: We cannot combine strings and numbers.
--
* To combine strings and numbers F-String was introduced in Python 3.6, and is now the preferred way of formatting strings.
* To specify a string as an f-string, simply put an f in front of the string literal, and add curly brackets {} as placeholders for variables and other operations.
* EX: age = 36
txt = f"My name is John, I am {age}"
print(txt)
--------------------------------------------------------------------
Placeholders and Modifiers: Placeholders are place in "{}" and modifier  is included by adding a colon : followed by a legal formatting type, like .2f which means fixed point number with 2 decimals:
--
* price = 59
txt = f"The price is {price} dollars"
print(txt)
* price = 59
txt = f"The price is {price:.2f} dollars"
print(txt)
* txt = f"The price is {20 * 59} dollars"
print(txt)

--------------------------------------------------------------------
ESCAPE CHARACTERS: escape characters are used to insert characters that are illegal in a string, such as newlines, tabs, or backslashes. 
--
* \'	Single Quote.
  * EX: txt = "We are the so-called \'Vikings\' from the north."
        print(txt)
  * Output: We are the so-called 'Vikings' from the north.
* \"	Double Quote
  * EX: txt = "We are the so-called \'Vikings\' from the north."
        print(txt)
  * Output: We are the so-called 'Vikings' from the north.
* "\\"	Backslash
  * path = "C:\\Users\\Name\\Documents"
  * print(path)
  * Output: C:\Users\Name\Documents
* \n	Newline
  * text = "This is a line.\nThis is a new line."
  * print(text)
  * Output: This is a line.
            This is a new line
* \t	Tab. Adds space between characters(string).
* \b	Backspace. moves back by one space between characters.

--------------------------------------------------------------------
String Methods: Operations done on strings. This will help modify string values. Convert to uper case, lower case, strip, split etc.....
--


