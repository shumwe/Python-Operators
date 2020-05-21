# Python-Operators
A documented summary of python operators

# Assignment operators - They are used to assign values to variables

a=9  
# assign the right side expression to the left side operand
b+=c 
# adds the right side operand with left side operand and assign to the left operand
b-=c 
# substracts the right side operand with left side operand and assign to the left operand
b*=c  
# multiplies the right operand with left operand and assign to the left operand
b/=c 
# devide the right side operand with left side operand and assign to the left operand
b%=c 
# takes module using left and right operand and assign results to the left


# Arithmetic operators- they are used to perform mathematical operations like addition, substraction, multiplication and division.
# Example of arithmetic operators

# Addition of numbers
add = x+y
# Substraction of numbers
sub = x-y
# Multiplication of numbers
mul = x*y
# Division (float) of numbers
div1 = x/y
# division (floor) of number
div2 = x//y
# Modulo of both nummbers
Mod = x%y

# Relative operators
# Used to compare values returning either true or false.
print(x>y)
# Return true if the left operand x is greater than the right
print(x<y)
# True if left operand x is less than right y
print(x==y)
# True if both operands are equal
print(x!=y) 
# True if operands x and y are not equal
print(x>=y)
# True if the left operand is greator than or equal to the right
print(x<=y)
# True if the left operand is less than or equal to the right

# Logical operators
# Example of logical opeator
b= True
d= False

print(b and d)
# returns false
print(b or d)
# returns true
print(not d)
# returns true

# Bitwise operators
x= 5
b= 3

print(x & b)
# print bitwise AND operation
print(x | b)
# print bitwise OR operation
print(~x)
# prints bitwwise not operation
print(x ^ b)
# prints bitwise XOR shift operation
print(x >> b)
# prints bitwise right shift operation
print(x << b)
# prints bitwise left shift operation

# Special operators
# Identity operators
x1 = 5
w1 = 5
x2 = 'Hello world'
w2 = 'Hello world'
x3 = [1,2,3]
w3 = [1,2,3]

print(x1 is not w1)
# Returns false
print(x2 is w2)
# Returns true
print(x3 is w3)
# Returns false since lists are mutable

# Membership operators
a = 'Get out of here'

print('ger' in a)
# returns false
print('out of' in a)
# returns true




