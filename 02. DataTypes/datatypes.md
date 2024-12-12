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


Example---Data Type
--
* x = "Hello World"---str	
* x = 20---int	
* x = 20.5---float	
* x = 1j---complex	
* x = ["apple", "banana", "cherry"]---list: values can be changed.
* x = ("apple", "banana", "cherry")---tuple: values can't be change, if want to then change to list. 
* x = range(6)---range	
* x = {"name" : "John", "age" : 36}---dict	
* x = {"apple", "banana", "cherry"}---set: duplicates nto allowed.
* x = frozenset({"apple", "banana", "cherry"})---frozenset	
* x = True---bool	
* x = b"Hello"---bytes	
* x = bytearray(5)---bytearray	
* x = memoryview(bytes(5))---memoryview	
* x = None---NoneType

Setting the Specific Data Type: If you want to specify the data type, you can use the following constructor functions:
--

Example---Data Type
--
* x = str("Hello World")---str	
* x = int(20)---int	
* x = float(20.5)---float	
* x = complex(1j)---complex	
* x = list(("apple", "banana", "cherry"))---list	
* x = tuple(("apple", "banana", "cherry"))---tuple	
* x = range(6)---range	
* x = dict(name="John", age=36)---dict	
* x = set(("apple", "banana", "cherry"))---set	
* x = frozenset(("apple", "banana", "cherry"))---frozenset	
* x = bool(5)---bool	
* x = bytes(5)---bytes	
* x = bytearray(5)---bytearray	
* x = memoryview(bytes(5)))---memoryview

--------------------------------------------------------
Inbuilt functions.
--
* type(): to check the type of variable
* id(): to get address of object
* print(): to print the value
* In Python everything is an Object.
--------------------------------------------------------
Python Numbers: There are three numeric types in Python:
--
* int
* float
* complex

Example:
--
* x = 1; y = 35656222554887711; z = -3255522    # int
* y = 2.8; y = 1.0; z = -35.59  # float
* z = 1+1j; J is imaginary here.   # complex

Note: You cannot convert complex numbers into another number type.
--
--------------------------------------------------------































