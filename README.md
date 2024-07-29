# Random-codes
'''Q1 Print the first 5 positive integers in ascending order with one number in each line.'''
n = int(input("enter te number of integers you want to print "))
for i in range(1,n+1):
    print(i)

'''Q2 Print the following pattern.
    *
    **
    ***
    ****
    *****
    There are no spaces between consecutive stars. There are no spaces at the end of each line.'''
n=int(input("enter the no of rows "))
for i in range(0,n):
    for j in range(0,i+1):
        print("*",end="")
    print()
'''Q3 Accept an integer as input and print its square as output.'''
n = int(input("enter the number whose square you want "))
m = n*n
print(m)
'''Q4 Accept two integers as input and print their sum as output.'''
n = int(input("Enter the first number "))
m = int(input("Enter the second number "))
a= n+m
print(a)
'''Q5 Accept two words as input and print the two words after adding a space between them.'''
a= input("enter the first word ")
b = input("enter the second word ")
print(a + " " + b)
'''Q6 Accept the registration number of a vehicle as input and print its state-code as output.'''
n= str(input("enter the vehicle registration number "))
print(n[0:2])
'''Q7 Accept a five digit number as input and print the sum of its digits as output.'''
n=input("enter a five digit number ")
a=int(n[0])
b=int(n[1])
c=int(n[2])
d=int(n[3])
e=int(n[4])
print(a+b+c+d+e)
'''Q8  Print the following pattern. There is exactly one space between any two consecutive numbers on any line. There are no spaces at the            
    end of any line.
    1 2 1
    1 2 3 2 1
    1 2 3 4 3 2 1
    1 2 3 4 5 4 3 2 1 '''
    
'''Q9 A simple algorithm has to be designed to find out whether a student belongs to the Data Science branch or not. The input will be a student's roll number, which is of the form  BR18B0000. Here, BR represents the branch code, 
   18
   18 represents the year of joining, B represents the education level and 
   0000
   0000 represents the specific identification given to the student of that batch. The branch code for Data Science is DS. Print True if the student belongs to Data Science branch and False  otherwise.'''

n=input("enter your roll number in capital ")
a='DS'

if a in n[0:2]:
    print("true")
else:
    print("FALSE")
'''Q10 The police are trying to track a criminal based on the evidence available at a crime site. Their main clue is a vehicle's damaged number plate. Only the string TN07 is visible. The format of the registration number is AA00AA00, where the first two letters are alphabets, next two are numbers, next two are again alphabets followed by two numbers at the end. A number plate is picked from a database of registration numbers and is given to you as input. Your task is to determine if this could belong to the criminal or not. Print True if the number plate contains TN07 and False otherwise.'''
n=(input("enter the vehicle registration number i AA00AA0000 format "))

if "TN07" in n[0:4]:
    print("True")
else:
    print("False")
'''Q11 Accept two integers
a and b
b as input and print the absolute difference of both the numbers. For example, if 
a=9,b=8
a=9,b=8, then the absolute difference is 
9−8=1
9−8=1. So, your output should be 1'''
a=44
b=int(input("enter b"))
print(a-b)
,,,Q12 You are given a string and two non-negative integers as input. The two integers specify the start and end indices of a substring in the given string. Create a new string by replicating the substring a minimum number of times so that the resulting string is longer than the input string. '''
x=input("Enter the string ")
a=int(input("enter the starting index of substring "))
b=int(input("enter the end index of substring "))
substring=x[a:b]
c=len(substring)
d=1
while len(substring * d) <= len(x)
d +=1
print(substring * d)
'''Q13 The following expression is called a continued fraction: x + 1/(x + 1/(x + 1/(x + 1/(x + 1/x))))
Accept a positive integer x
x as input, compute the value of this continued fraction and store the result in a variable named cfrac. We will round off your answer to exactly two decimal places.'''
x=int(input("Enter value of x"))
c=x + 1/(x + 1/(x + 1/(x + 1/(x + 1/x))))
print(c)
'''Q14 Assume that several IITs start offering online degrees across multiple branches. The email-id of a student is defined as follows:
branch_degree_year_roll@student.degree.institute.ac.in
For example, if the email-id is CS_BT_21_7412@student.onlinedegree.gug.ac.in, then this student is from the computer science branch, pursuing a BTech degree from GUG, starting from the year 2021, with 7412 as the roll number. branch, degree and year are codes of length two, while roll and institute are codes of length four. Accept a student's email-id as input and print the following details, one item on each line:

(1) Branch
(2) Degree
(3) Year
(4) Roll number
(5) Institute'''
Email=input("Enter your email ")
Branch = Email[0:2]
print(Branch)
Degree = Email[3:5]
print(Degree)
Year = Email[6:8]
print(Year)
Rollno = Email[9:13]
print(Rollno)
Institute = Email[35:38]
print(Institute)
'''Q15 Accept two positive integers x and y as input. Print the number of digits in xy.'''
x=input("Enter the number ")
y=input("Enter the number ")
a=len(x)
b=len(y)
print(a*b)
'''Q16 Accept an integer as input. Print positive if it is greater than zero and negative if it is less than zero. You can assume that the input will be non-zero.'''
x= int(input("Enter the number "))
if x < 0:
    print("x is negative")
elif x> 0:
    print("x is positive")
else:
    print("x is equal to zero")
'''Q17 '''
x= int(input("Enter the number "))
if x > 0 and x < 10 :
    print(x+2)
elif x> 10:
    print((x*x) + 2)
else:
    print(0)
'''Q18'''
t= int(input("Enter the T "))
if t< 0:
    print("INVALID")
elif t>=0 and t<=5:
    print("NIGHT")
elif t>=6 and t<=11:
    print("MORNING")
elif t>=12 and t<=17:
    print("AFTERNOON")
elif t>=12 and t<=23:
    print("EVENING")
else:
    print("INVALID")
'''Q19'''





    




    
