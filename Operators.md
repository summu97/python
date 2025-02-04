**Operators**
--

Arithmetic operators: Arithmetic operators are used with numeric values to perform common mathematical operations
--
* Addition:  +
* Subtraction:  -
* Multiplication:  *
* Division:  /
* Modulus:  %  ---- gives the remainder
* Exponential:  **  ---- 2 ** 3 # same as 2*2*2 
* Floor division:  //  ----- #the floor division // rounds the result down to the nearest whole number i.e, 15 // 7 = 2

Assignment operators: Assignment operators are used to assign values to variables.
--
* =
* +=  (x += 3	x = x + 3)
* -=  (x -= 3	x = x - 3)
* *=  (x *= 3	x = x * 3)
* /=  (	x /= 3	x = x / 3)
* %=  (x %= 3	x = x % 3)
* //= (	x //= 3	x = x // 3)
* **= (	x **= 3	x = x ** 3)
* &=  (x &= 3	x = x & 3) ?
* |=  (x |= 3	x = x | 3) ?
* ^=  (	x ^= 3	x = x ^ 3) ?
* >>= (	x >>= 3	x = x >> 3) ?
* <<= (x <<= 3	x = x << 3) ?
* :== (	print(x := 3)	x = 3	print(x))

Comparison operators: Used to compare two values.
--
* ==	Equal	x == y	
* !=	Not equal	x != y	
* >	Greater than	x > y	
* <	Less than	x < y	
* >=	Greater than or equal to	x >= y	
* <=	Less than or equal to	x <= y

Logical operators: Used to combine conditional statements.
--
* and 	Returns True if both statements are true	x < 5 and  x < 10	
* or	Returns True if one of the statements is true	x < 5 or x < 4	
* not	Reverse the result, returns False if the result is true	not(x < 5 and x < 10)

Identity operators: Identity operators are used to compare the objects, not if they are equal, but if they are actually the same object, with the same memory location.
--
* is 	Returns True if both variables are the same object	x is y	
* EX:
	* x = ["apple", "banana"]
	* y = ["apple", "banana"]
	* z = x

	* print(x is z) # returns True because z is the same object as x

	* print(x is y) # returns False because x is not the same object as y, even if they have the same content

	* print(x == y) # to demonstrate the difference betweeen "is" and "==": this comparison returns True because x is equal to y
* is not	Returns True if both variables are not the same object
* EX:
	* x = ["apple", "banana"]
	* y = ["apple", "banana"]
	* z = x

	* print(x is not z) # returns False because z is the same object as x

	* print(x is not y) # returns True because x is not the same object as y, even if they have the same content

	* print(x != y) # to demonstrate the difference betweeen "is not" and "!=": this comparison returns False because x is equal to y

Membership operators: Membership operators are used to test if a sequence is presented in an object.
--
* in 	Returns True if a sequence with the specified value is present in the object	x in y
* EX:
	* x = ["apple", "banana"]
	* print("banana" in x) # returns True because a sequence with the value "banana" is in the list	
* not in	Returns True if a sequence with the specified value is not present in the object
* EX: 
	* x = ["apple", "banana"]
	* print("pineapple" not in x) # returns True because a sequence with the value "pineapple" is not in the list


Bitwise operators: Bitwise operators are used to compare (binary) numbers.
--

Operator Precedence: Sequence in which operations are done.
--
* For Arithmetic operators it follows BODMAS rule.
* For Logical operators the series is and, or, not.
====================================================
====================================================
