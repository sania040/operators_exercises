# Subject of the python script: Practice Questions of Python Operators
# Authored by: Sania Shakeel
# Where to contact: shakeelsania040@gmail.com   and   https://github.com/sania040


# Question 1 -> Write a program that accepts two numbers as input and  find their sum, defference, quotient, product,and remainder?

# Step 1: take two numbers as input
a = 2
b = 5

# Step 2: perform operations
# Sum 
print(a+b)

# difference
print(a-b)

# Quotient
print(a/b) #this will produce float qoutient
print(a//b) #this will produce int quotients

# product
print(a*b)
 
# remainder
print(a%b) 

'''
'''
# Question 2-> write a program to check if the number is even or odd

# Step 1: Get input 
a = 5

# Step 2: check if it's even
if ( a % 2 == 0):
    print("Even")
#Step 3: if not even tell that it's odd.
else: 
    print("odd") 

# Question 3 -> Implement a script to convert celsius into farenhiet

# Step 1: Get input temprature in celsius
celsius = 23

# Step 2: Implement logic
farenheit = (celsius * 1.8)  + 32

#Step 3: Print Farenheit Output
print(farenheit)

# Question 4 -> Write a program to find area of a triangle given its height and base

# Step 1: Give Base and height
base = 5
height = 5

# Step 2: Implement logic
area = (1/2) * base * height

# Step 3: Print area of traingle
print(str(area ) + "cm")  # the float or nonstring values must be casted to string for concatenation.

# Question 5 -> Write a Script to input two numbers and check if the first if greater than,less than or equal to second

#Step 1: Input two numbers
num1 = 5
num2 = 10

# Step 2: Check if equal to
if (num1 == num2 ): 
    print("Equal")
# Step 3: Check if it's less than
elif (num1 < num2):
    print("Less than")
# Step 4: if it's nor equal nor less than It must be greater than
else:
    print("Greater than")
# Question 6 -> Write a script to calculate the square and cube of the given numbers
# HINT: ** operator is exponent operator

# Step 1: Get input 
num = int(input("Enter number")) #the input() returns string by defalut, we need to type caste it to int

# Step 2: find Square
square = num**2
print("Square : " + str(square)) # to concetente a non-string value with string we need to type caste it to string

# Step 3: find cube
cube = num**3
print("Cube : "+ str(cube))

# Question 7 -> Implement a program which converts minutes into hours and minutes

# Step 1: Take input and initialize hours counter
minute = int(input("Enter minutes: "))
hour = 0

# Step 2: Implement logic
# Check if minutes are more than 60 or 1 hour
if(minute >= 60 ): 
    while(minute > 60):  # loop until the minutes are greater than 60
         minute -= 60    # delete 60 from minutes
         hour += 1        #  add 1 in hour count
    
print(str(hour) + " hours " + str(minute) + " minutes ") 


# Question 8 -> Write a script to check if the number is multiple of both 3 and 5

# Step 1: Get input 
num = int(input("Enter number: "))

# Step 2: Build logic
# Check if the number is multiple of 3 and 5

if (num % 5 == 0 and num % 3 == 0 ):
    print(True)
else:
    print(False)

