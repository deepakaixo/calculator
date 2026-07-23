#Create a simple calculator and firstly take two inputs numbers from user
a=float(input("enter first number:"))
b=float(input("enter second number:"))
#take input for operation which operation user perform
OPR=input(("enter operation do you perform(+,-,*,/):"))
#let's check conditions and operate operations on numbers
if OPR=="+":
 print("result=",a+b)
elif(OPR=="-"):
 print("result=",a-b)
elif(OPR=="*"):
 print(("result=",a*b))
elif(OPR=="/"):
 if(b!=0):
    print("result:",a/b)
else:
     print("error")


