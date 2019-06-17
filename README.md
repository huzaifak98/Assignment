Name: Huzaifa Ali Khan
PIAIC Roll #: AIC011344
Campus:Adamjee Institute
Section:Sunday:12 15-3 15
Teacher:Sir Inam

# Assignments

assignment 1

Generate a simple Calculator:

a=int(input("Enter 1st number "))
b=int(input("Enter 2nd number "))
operator=input("Enter operator from the following +,-,/,*,% \n")
if operator=='+':
    print(a+b)
elif operator=='-':
    print(a-b)
elif operator=='*':
   print(a*b)
elif operator=='/':
    print(a/b)
elif operator=='%':
    print(a%b)

Generate a marksheet with percentage and grading:

sub1=int(input("Enter English marks "))
sub2=int(input("Enter Urdu marks "))
sub3=int(input("Enter Maths marks "))
sub4=int(input("Enter Physics marks "))
print("      MARKSHEET ") 
print(" ========================")
print("| Eng\t\t"+str(sub1)+" \t |")
print("| Urd\t\t"+str(sub2)+" \t |")
print("| Mat\t\t"+str(sub3)+" \t |")
print("| Phy\t\t"+str(sub4)+" \t |")
per=(sub1+sub2+sub3+sub4)/4
if(per>=80):
    Grade=("A+")
elif(per>=70 and per<80):
    Grade=("A")
elif(per>=60 and per<70):
    Grade=("B")
elif(per>=50 and per<60):
    Grade=("C")
else:
    Grade=("F")
print("|\t    \t    \t | \n| Grade:"+str(Grade)+" Per:"+str(per)+"%\t |")
print(" ========================")

assignment 2

Generate a table of an input number:

a=int(input("Enter a number to generate its table: "))
for b in range(1,11):
        print(str(a)+" x "+str(b)+" = "+str(a*b))
print("--------------")

Get a number input from user and check if its Prime or not

c=0
x=int(input("Enter a number "))
for a in range(2,x):
    if x%a==0:
        print("Not Prime")
        break
    else:
        c=c+1
        continue
if c>0:
    print("Prime")

 fill a list with random numbers and then remove a number so that all occurrences of that number are removed from the list
 
 list1=[1,3,4,5,6,3,5,6,5,3,3,35,4,3,3,13,13,1,13,31,13,4,5,3,23,53,4]
for b in list1:
    if b==3:
        (list1.remove(3))

print(list1)
