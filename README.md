# Random-codes
#Print the first 5 positive integers in ascending order with one number in each line.
n = int(input("enter te number of integers you want to print "))
for i in range(1,n+1):
    print(i)

#Print the following pattern.
    *
    **
    ***
    ****
    *****
    There are no spaces between consecutive stars. There are no spaces at the end of each line.
n=int(input("enter the no of rows "))
for i in range(0,n):
    for j in range(0,i+1):
        print("*",end="")
    print()
    
