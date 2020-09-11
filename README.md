# Addition-of-two-numbers
#Python program to add two numbers

num1=int(input("Enter 1st Number:"))
num2=int(input("Enter 2nd Number:"))
def add(num1,num2):
    sum=num1+num2
    return sum
    
ans=add(num1,num2)
print("Addition of {0} and {1} is {2}".format(num1,num2,ans))
