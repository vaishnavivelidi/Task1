#program 1 Check whether employee age is above 21 and salary is above 30000
age=int(input())
salary=int(input())
print(age>21 and salary>30000)
#program 2 Check whether student passed in two subjects
sub1=int(input())
sub2=int(input())
print(sub1>35 and sub2>35)
# program 3 Check whether entered value is between two ranges
a=int(input())
if a in range(1,10):
    print("true")
else:
    print("false")
#program 4  Check whether username and password are correct
username=input()
passw=int(input())
print((username=="deepika") and (passw==123))
#program 5  Check whether temperature is within safe range
temperature=int(input())
if temperature in range(20,50):
    print("safe")
else:
    print("dangeor")
# program 6 Check whether both entered numbers are even
a=int(input())
b=int(input())
print(a%2==0 and b%2==0)
#program 7 check whether both entered numbers are positive
a=int(input())
b=int(input())
print(a>0 and b>0)
#program 8 Check whether person is eligible for driving
age=int(input())
test=input()
print(age>=18 and test=="pass")
#program 9 roject progress meets deadline conition
remainingdays=int(input())
percentage=int(input())
print(remainingdays>5 and percentage>80)
#program 10 Check whether attendance and marks satisfy eligibility
marks=int(input())
attendence=int(input())
print(marks>75 and attendence>76)
#program 11 Check whether entered role is Admin or Manager
person=input()
print(person=="manager" or person=="admin")
# program 12 check whether student scored distinction in any one subject
sub1=int(input())
sub2=int(input())
sub3=int(input())
print(sub1>75 or sub2>75 or sub3>75)
#program 13 Check whether entered day is weekend
day=input()
print(day=="sunday" or day=="saturday")
#program 14 Check whether selected category matches two possible values
category = input("Enter category: ")
print(category == "Electronics" or category == "Clothing")
# program 15 Check whether salary or experience satisfies requirement
salary=int(input())
experience=int(input())
print(salary==50000 or experience==5)
# program 16 Check whether temperature is extremely low or high
temp=int(input())
print(temp<0 or temp>40)
#program 17 Check whether entered username matches predefined values
user=input()
print(user=="deepika" or user=="sharon" or user =="rani")
#program 18 Check whether selected option belongs to given choices
option=input()
print(option=="teacher" or option=="student" or option=="admin")
# program 19 Check whether entered city matches allowed cities
city=input()
print(city=="hyderabad"or city=="chennai" or city=="benglore")
# program 20 Check whether entered number matches predefined values
num=int(input())
print(num==1 or num==3 or num==5)
# program 21 Check whether user is not admin
user=input()
print(not user== "admin")
# program 22 Check whether entered number is not positive
num=input()
print(not (num>="0"))
#program 23  Check whether entered value is not empty
value = input("Enter value: ")
print (not value == "")
# program 24  Check whether file is not available
file=False
print(not file)
#program 25 Check whether employee is not active
employe=False
print(not employe)
# program 26 Check whether project status is not completed
status = input("Enter project status: ")
print(not status == "Completed")
# program 27 Check whether password is not correct
password=int(input())
print(password=="1234")
#program 28 Check whether temprature safe
temperature=int(input())
print(not temperature>50)
# program 29  Check whether selected option is not allowed
option=input()
print(not option=="user" )
# program 30 Check whether marks are not passing marks
marks=int(input())
print(not marks>35)