Q1. How do you comment code in Python? What are the different types of comments?

n Python, you can comment code using the # symbol for single-line comments. For multi-line comments, you can use triple quotes (''' or """).
Single-line comment:
python
Copy code
# This is a single-line comment
Multi-line comment:
python
Copy code
"""
This is a
multi-line comment
"""
or
python
Copy code
'''
This is a
multi-line comment

Q2. What are variables in Python? How do you declare and assign values to variables?
Variables in Python are used to store data values. You declare a variable by simply assigning a value to it using the equals sign (=). Python infers the variable type based on the assigned value.
Example:
python
Copy code
x = 10         # Integer
name = "Alice" # String
pi = 3.14      # Float

Q3. How do you convert one data type to another in Python?

In Python, you can convert one data type to another using type conversion functions such as int(), float(), str(), and list().
Examples:
python
Copy code
x = 5.6
y = int(x)       # Convert float to int

s = "123"
n = int(s)       # Convert string to int

num = 42
s = str(num)     # Convert int to string

Q4. How do you write and execute a Python script from the command line?
To write a Python script, create a file with a .py extension containing your code. To execute it from the command line:
1.	Open the command line interface.
2.	Navigate to the directory containing the script.
3.	Run the script using:
sh
Copy code
python script_name.py
Replace script_name.py with your file name.
Q5. Given a list my_list = [1, 2, 3, 4, 5], write the code to slice the list and obtain the sub-list [2, 3].
You can slice a list in Python using square brackets []. The syntax for slicing is list[start_index:end_index], where start_index is inclusive and end_index is exclusive. Here's how you can obtain the sub-list [2, 3] from my_list = [1, 2, 3, 4, 5]:
python
Copy code
my_list = [1, 2, 3, 4, 5]
sub_list = my_list[1:3]  # Slice from index 1 (inclusive) to index 3 (exclusive)
print(sub_list)  # Output: [2, 3]
In this example:
•	my_list[1:3] slices the list from index 1 (which is 2) up to, but not including, index 3 (which is 4).
•	This results in the sub-list [2, 3].

Q6. What is a complex number in mathematics, and how is it represented in Python?
In mathematics, a complex number is a number that can be expressed in the form a+bia + bia+bi, where aaa and bbb are real numbers, and iii is the imaginary unit satisfying i2=−1i^2 = -1i2=−1.
In Python, complex numbers are represented using the syntax a + bj, where a and b are real numbers and j is the imaginary unit.
Q7. What is the correct way to declare a variable named age and assign the value 25 to it?
In Python, you declare a variable by assigning a value to it using the equal sign (=). To declare a variable named age and assign the value 25 to it, you would write:
python
Copy code
age = 25
Here, age is the variable name, and 25 is the assigned value.
Q8. Declare a variable named price and assign the value 9.99 to it. What data type does this variable
belong to?
To declare a variable named price and assign the value 9.99 to it in Python, you would write:
python
Copy code
price = 9.99
In Python, the variable price belongs to the data type float because 9.99 is a floating-point number. Floats represent real numbers and are used for values that require decimal precision.
Q9. Create a variable named name and assign your full name to it as a string. How would you print the
value of this variable?
To create a variable named name and assign your full name to it as a string in Python, you would write:
python
Copy code
name = "Your Full Name"
Replace "Your Full Name" with your actual full name enclosed in double quotes.
To print the value of this variable, you can use the print() function:
python
Copy code
print(name)
For example, if your full name is "John Doe", the code would look like this:
python
Copy code
name = "John Doe"
print(name)  # Output: John Doe
This will print your full name stored in the name variable.
Q10. Given the string "Hello, World!", extract the substring "World".

To extract the substring "World" from the string "Hello, World!" in Python, you can use string slicing. Here's how you can achieve this:
python
Copy code
s = "Hello, World!"
substring = s[7:12]
print(substring)  # Output: World
In this example:
•	s[7:12] slices the string s from index 7 (inclusive) to index 12 (exclusive), extracting the substring "World".

Q11. Create a variable named "is_student" and assign it a boolean value indicating whether you are
currently a student or not.

To create a variable named is_student and assign it a boolean value in Python, indicating whether you are currently a student or not, you would write:
python
Copy code
is_student = True
Set is_student to True if you are currently a student, or False if you are not. Boolean values in Python represent true or false states.


