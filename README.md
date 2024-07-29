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
    




    
