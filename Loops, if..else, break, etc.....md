## Conditions: These conditions can be used in several ways, most commonly in "if statements" and loops.

- Equals: a == b
- Not Equals: a != b
- Less than: a < b
- Less than or equal to: a <= b
- Greater than: a > b
- Greater than or equal to: a >= b

## If ... Else: An "if statement" is written by using the if keyword.
- if Syntax: 
- if <condition>:
-   print("...msg...")

- EX:
  - a = 33
  - b = 200
  - if b > a:
  -   print("b is greater than a")

- NOTE: Make sure you put ":" at last of if - block and also two white spaces before print statement.

Elif:
--
elif Syntax: Same as "if" statement
--
- EX:
  - a = 33
  - b = 33
  - if b > a:
  -   print("b is greater than a")
  - elif a == b:
  -   print("a and b are equal")

Else:
--
- else Syntax:
- else:
-   print("...msg...")

- EX:
  - a = 200
  - b = 33
  - if b > a:
  -   print("b is greater than a")
  - elif a == b:
  -   print("a and b are equal")
  - else:
  -   print("a is greater than b")

Short Hand If: If you have only one statement to execute, you can put it on the same line as the if statement.
--
- Ex: if a > b: print("a is greater than b")

Short Hand If ... Else: If you have only one statement to execute, one for if, and one for else, you can put it all on the same line.
--
- EX:
  - a = 2
  - b = 330
  - print("A") if a > b else print("B")

- NOTE: This technique is known as Ternary Operators, or Conditional Expressions.

One line if else statement, with 3 conditions:
--
- a = 330
- b = 330
- print("A") if a > b else print("=") if a == b else print("B")

And: The and keyword is a logical operator, and is used to combine conditional statements:
--
- Test if a is greater than b, AND if c is greater than a:
  - a = 200
  - b = 33
  - c = 500
  - if a > b and c > a:
  -   print("Both conditions are True")

Or: The or keyword is a logical operator, and is used to combine conditional statements:
--
- Test if a is greater than b, OR if a is greater than c:
  - a = 200
  - b = 33
  - c = 500
  - if a > b or a > c:
  -   print("At least one of the conditions is True")

Not: The not keyword is a logical operator, and is used to reverse the result of the conditional statement:
--
- Test if a is NOT greater than b:
- a = 33
- b = 200
- if not a > b:
-   print("a is NOT greater than b")

Nested If: You can have if statements inside if statements, this is called nested if statements.
--
- x = 41

- if x > 10:
-   print("Above ten,")
-   if x > 20:
-     print("and also above 20!")
-   else:
-     print("but not above 20.")

The pass Statement: if statements cannot be empty, but if you for some reason have an if statement with no content, put in the pass statement to avoid getting an error.
--
- a = 33
- b = 200

- if b > a:
-   pass
- NOTE: The pass statement in Python does nothing. It's a placeholder used when you need to write code but don't want to do anything in that block yet.  
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Loops:
--
- Python has two primitive loop commands:
 - while loops
 - for loops

The while Loop: We can execute a set of statements as long as a condition is true.
--
- Print i as long as i is less than 6:

 - i = 1
 - while i < 6:
 -   print(i)
 -   i += 1
- NOTE: remember to increment i, or else the loop will continue forever.

The break Statement: With the break statement we can stop the loop even if the while condition is true:
--
- Exit the loop when i is 3:
- i = 1
- while i < 6:
-   print(i)
-   if i == 3:
-     break
-   i += 1

The continue Statement: With the continue statement we can stop the current iteration, and continue with the next:
--
- Continue to the next iteration if i is 3:
- i = 0
- while i < 6:
-   i += 1
-   if i == 3:
-     continue
-   print(i)

The else Statement: With the else statement we can run a block of code once when the condition no longer is true:
--
- Print a message once the condition is false:
- i = 1
- while i < 6:
-   print(i)
-   i += 1
- else:
-   print("i is no longer less than 6")

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## For Loops:
- Loop through the letters in the word "banana":

  - for x in "banana":
  -   print(x)

## Exit the loop when x is "banana":

  - fruits = ["apple", "banana", "cherry"]
  - for x in fruits:
  -   print(x)
  -   if x == "banana":
  -     break

## Do not print banana:

  - fruits = ["apple", "banana", "cherry"]
  - for x in fruits:
  -   if x == "banana":
  -     continue
  -   print(x)

## Using the range() function:

  - for x in range(6):
  -   print(x)

## Using the start parameter:

  - for x in range(2, 6):
  -   print(x)

## Increment the sequence with 3 (default is 1):

  - for x in range(2, 30, 3):
  -   print(x)

## Print all numbers from 0 to 5, and print a message when the loop has ended:

  - for x in range(6):
  -   print(x)
  - else:
  -   print("Finally finished!")

## Break the loop when x is 3, and see what happens with the else block:

  - for x in range(6):
  -   if x == 3: break
  -   print(x)
  - else:
  -   print("Finally finished!")

#If the loop breaks, the else block is not executed.

## Print each adjective for every fruit:

  - adj = ["red", "big", "tasty"]
  - fruits = ["apple", "banana", "cherry"]

  - for x in adj:
  -   for y in fruits:
  -     print(x, y)


















