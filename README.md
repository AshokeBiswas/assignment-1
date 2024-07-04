Q1. Create one variable containing following type of data:
Ans:
data = {
    "string": "Hello, World!",
    "list": [1, 2, 3, 4, 5],
    "float": 3.14,
    "tuple": (10, 20, 30)}
In this dictionary:
•	The key "string" holds a string value.
•	The key "list" holds a list.
•	The key "float" holds a float value.
•	The key "tuple" holds a tuple.
Q2. Given are some following variables containing data:
i) var1 = ' '
•	Type: str (string)
(ii) var2 = '[ DS , ML , Python]'
•	Type: str (string)
(iii) var3 = [ 'DS' , 'ML' , 'Python' ]
•	Type: list (list of strings)
(iv) var4 = 1.
•	Type: float
Here is the Python code to verify the types of these variables:
python
Copy code
var1 = ' '
var2 = '[ DS , ML , Python]'
var3 = [ 'DS', 'ML', 'Python' ]
var4 = 1.

print(type(var1))  # Output: <class 'str'>
print(type(var2))  # Output: <class 'str'>
print(type(var3))  # Output: <class 'list'>
print(type(var4))  # Output: <class 'float'>

Q3. Explain the use of the following operators using an example:
(i) / - Division Operator
The / operator is used to divide one number by another and returns a float result.
Example:
python
Copy code
a = 10
b = 3
result = a / b
print(result)  # Output: 3.3333333333333335
(ii) % - Modulus Operator
The % operator is used to find the remainder when one number is divided by another.
Example:
python
Copy code
a = 10
b = 3
result = a % b
print(result)  # Output: 1
(iii) // - Floor Division Operator
The // operator is used to divide one number by another and returns the largest integer less than or equal to the result (i.e., it performs floor division).
Example:
python
Copy code
a = 10
b = 3
result = a // b
print(result)  # Output: 3
(iv) ** - Exponentiation Operator
The ** operator is used to raise one number to the power of another.
Example:
python
Copy code
a = 2
b = 3
result = a ** b
print(result)  # Output: 8
In summary:
•	/ divides and returns a float.
•	% returns the remainder of a division.
•	// performs floor division and returns an integer.
•	** raises one number to the power of another.
Q4. Create a list of length 10 of your choice containing multiple types of data. Using for loop print the
element and its data type.

# Creating a list with multiple types of data
my_list = [42, "Hello", 3.14, True, None, [1, 2, 3], {'a': 1, 'b': 2}, (4, 5), {9, 8, 7}, b"bytes"]

# Using a for loop to print each element and its data type
for element in my_list:
    print(f"Element: {element}, Type: {type(element)}")
Output:
python
Copy code
Element: 42, Type: <class 'int'>
Element: Hello, Type: <class 'str'>
Element: 3.14, Type: <class 'float'>
Element: True, Type: <class 'bool'>
Element: None, Type: <class 'NoneType'>
Element: [1, 2, 3], Type: <class 'list'>
Element: {'a': 1, 'b': 2}, Type: <class 'dict'>
Element: (4, 5), Type: <class 'tuple'>
Element: {8, 9, 7}, Type: <class 'set'>
Element: b'bytes', Type: <class 'bytes'>
Q5. Using a while loop, verify if the number A is purely divisible by number B and if so then how many
times it can be divisible.

A = 100  # Example value for A
B = 5    # Example value for B

count = 0  # Counter to keep track of the number of times A is divisible by B

# Verify if A is divisible by B
while A % B == 0:
    A = A // B  # Divide A by B
    count += 1  # Increment the counter

print(f"The number can be divisible {count} times.")
In this example:
•	A is initially 100 and B is 5.
•	The while loop continues to divide A by B as long as A is divisible by B.
•	The counter count keeps track of the number of times A is divisible by B.
•	Finally, the script prints how many times A can be divisible by B.
Q6. Create a list containing 25 int type data. Using for loop and if-else condition print if the element is
divisible by 3 or not.

# Creating a list of 25 integers
int_list = list(range(1, 26))  # This creates a list with numbers from 1 to 25

# Using a for loop to check if each element is divisible by 3
for number in int_list:
    if number % 3 == 0:
        print(f"{number} is divisible by 3.")
    else:
        print(f"{number} is not divisible by 3.")
Output:
csharp
Copy code
1 is not divisible by 3.
2 is not divisible by 3.
3 is divisible by 3.
4 is not divisible by 3.
5 is not divisible by 3.
6 is divisible by 3.
7 is not divisible by 3.
8 is not divisible by 3.
9 is divisible by 3.
10 is not divisible by 3.
11 is not divisible by 3.
12 is divisible by 3.
13 is not divisible by 3.
14 is not divisible by 3.
15 is divisible by 3.
16 is not divisible by 3.
17 is not divisible by 3.
18 is divisible by 3.
19 is not divisible by 3.
20 is not divisible by 3.
21 is divisible by 3.
22 is not divisible by 3.
23 is not divisible by 3.
24 is divisible by 3.
25 is not divisible by 3.
Q7. What do you understand about mutable and immutable data types? Give examples for both showing
this property.

1.	my_list = [1, 2, 3]
2.	print("Original list:", my_list)
3.	
4.	my_list[0] = 10  # Modifying the first element
5.	print("Modified list:", my_list)
6.	Output:
less
Copy code
Original list: [1, 2, 3]
Modified list: [10, 2, 3]
7.	Dictionary:
python
Copy code
my_dict = {'a': 1, 'b': 2}
print("Original dictionary:", my_dict)

my_dict['a'] = 10  # Modifying the value associated with key 'a'
print("Modified dictionary:", my_dict)
Output:
css
Copy code
Original dictionary: {'a': 1, 'b': 2}
Modified dictionary: {'a': 10, 'b': 2}
Immutable Data Types
Immutable data types are those whose values cannot be changed after they are created. Common immutable data types in Python include integers, floats, strings, tuples, and frozensets.


