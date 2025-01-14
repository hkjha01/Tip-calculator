# Bill-calculator
Project 1 bill calculator
print("welcome to tip calculator")
a= int(input("enter the bill amount:"))
b= int(input("Select tip % :"))
c=(a+a*(b/100))
d=int(input("enter no. of people to split between:"))
e=c/d
print("Amount per head=",e)
