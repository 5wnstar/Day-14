# Day-14
30 Days of codding 

1.0 THE PRINT STATEMENT OR FUNCTION IN PYTHON 

The print() function or statement in Python is I think the most used statement in my perspective. Because every time we need to produce or print some output, the print() function is required. This article teaches you everything about this function.
Definition of print() Function

The print() function is used to produce output.

1.1  DEFINITION OF print() FUNCTION 

The print() function is used to produce output. For example:

print("Hey!\nWelcome to Cyb3r_J0ll0f 30 days of codding")

CHECK THE FILE "Print.py" to see the source codes 

1.2 SYNTAX OF print() FUNCTION
The syntax to use print() function is:

print(value(s), sep=' ', end='\n')

Note - Except value(s), all other parameters are optional. Even value(s) is also optional. That is, print() doesn't produce any error if you doesn't provide any parameter to it. But if you doesn't provide any value/expression, then the output will be nothing or blank for that print() statement.


In above syntax of print(). Here are the description of all the parameters one by one.
The value(s)/expression(s) Parameter

This is the most used parameter. Any number of value/expression can be passed. That is, the expression passed in print() is not limited to only one. That is, you can pass any number of expressions to print() where expression must be separated by a comma as shown in the program given below:

print("Hey!", "\nWelcome to Cyb3r_J0ll0f 30 Days of Codding")

produces the same output as of very first program of this article.

Note - The print() function converts all the expressions passed in it, into a string before writing or printing the things to the output screen.
print statement in python

1.2.1  THE sep= PARAMETR

Now the second parameter is sep=' '. It is used to separate expression using manually assigned character or combination of characters. To learn more about it, refer to sep parameter in Python. If you doesn't use or provide this parameter to print(). Then by default, all expression gets separated by a single space.
The end= Parameter

1.2.2 THE end='\n' PARAMETER. 
It is used to skip insertion of an automatic newline using print() on the output screen. To learn more about it, refer to end parameter in Python. If you doesn't use it, then after each print() statement, a newline automatically gets inserted on output screen.

1.3 print() Function Example

Here is an example of print() function that uses all the parameters as shown in its syntax given above:

print("Hello", 123, "How are you?", sep="\n", end="\n", "This Cyb3r_J0ll0f")

