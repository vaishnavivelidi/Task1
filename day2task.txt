#DAY - 2 TASKS - BIM ERA 
''''
#1.  Check Employee promotion eligibility
age = int (input("enter the age:"))
experiance = int(input("enter the experiance:"))
salary = int(input("enter the salary:"))
if age > 30 and experiance > 5 and salary > 50000:
    print("eligible for promotion")
else:
    print("not eligible for promotion")
    
#2.Check student distinction category
maths = int(input("enter your marks in maths:"))
science = int(input("enter your marks in science:"))    
english = int(input("enter your marks in english:"))
if maths>= 75 and science >= 75 and english >= 75:
    print("you are in distinction category")
else:
    print("you are not in distinction category")
    
#3. Check website login system
username = input("enter your username:")
password =input("enter your password:")
otp = int(input("enter the otp:"))
if username=="admin" and password==1234 and otp == 567:
    print("login successful")
else:
    print("login failed")
    
#4. Check internet package category
speed = int(input("enter your internet speed in Mbps:"))
data_usage = int(input("enter your data usage in GB:"))
remaining_days = int(input("enter the remaining days in your billing cycle:"))
if speed >= 100 and data_usage <= 500 and remaining_days > 10:
    print("you are in premium package")
elif speed >= 50 and data_usage <= 200 and remaining_days > 5:
    print("you are in standard package")
else:
    print("you are in basic package")
    
#5.Check job eligibility
degree_availbility = input("do you have a degree? (yes/no):")
experience  = int(input("enter your years of experience:"))
age =   int (input("enter your age:"))
if degree_availbility.lower() == "yes" and experience >= 3 and age >= 25:
    print("you are eligible for the job")
else:
    print("you are not eligible for the job")
    
#6. Check flight boarding eligibility
ticket_availability = input("do you have a valid ticket? (yes/no):")
passport_availability = input("do you have a valid passport? (yes/no):")
luggage_weight = float(input("enter your luggage weight in kg:"))
if ticket_availability.lower() == "yes" and passport_availability.lower() == "yes" and luggage_weight <= 20:
    print("you are eligible for flight boarding")
else:
    print("you are not eligible for flight boarding")
    
#7. Check scholarship eligibilit
marks = int(input("enter your marks:"))
family_income = float(input("enter your family income in lakhs:"))
attendance = float(input("enter your attendance percentage:"))
if marks >= 85 and attendance >= 90 and family_income <= 300000:
    print("you are eligible for the scholarship")
else:
    print("you are not eligible for the scholarship")
    
#8. Check mobile unlock system
pin = int(input("enter your pin:"))
face_detection_status = input("is face detection available? (yes/no):")
fingerprint_status = input("is fingerprint recognition available? (yes/no):")
if pin == 1234 or face_detection_status.lower()== "yes" or fingerprint_status.lower() == "yes":
    print("unlocked ")
else:
    print("locked")
    
#9.Check hotel booking eligibility
number_of_rooms = int(input("enter the number of rooms:"))
number_of_days = int(input("enter the number of days for stay:"))
budget = int(input("enter your budget in dollars:"))
if number_of_rooms >= 2 and number_of_days >= 3 and budget >= 500:
    print("luxury booking")
elif number_of_rooms >= 1 and number_of_days >= 2 and budget >= 200:
    print("standard booking")
else:
    print("budget booking")
    
#10. Check exam topper category
subject1_marks = int(input("enter your marks in subject 1:"))
subject2_marks = int(input("enter your marks in subject 2:"))
subject3_marks = int(input("enter your marks in subject 3:"))
total_marks = subject1_marks + subject2_marks + subject3_marks
if total_marks >= 270:
    print("TOPPER")
elif total_marks >= 180:
    print("AVG")
else:
    print("NEEDS IMPROVEMENT")
    
#11.Check gym membership category
age = int(input("enter your age:"))
weight = float(input("enter your weight in kg:"))
height = float(input("enter your height in cm:"))
if age >= 18 and weight >= 50 and height >= 150:
    print("fitness category a ")
elif age >= 16 and weight >= 40 and height >=140:
    print("fitness category b")
else:
    print("fitness category c")
    
#12.Check traffic penalty system
helmet_status = input("do you have a helmet? (yes/no):")
license_status = input("do you have a valid license? (yes/no):")
speed = int(input("enter your speed in km/h:"))
if helmet_status.lower() == "yes" and license_status.lower() == "yes" and speed <= 80:
    print("no fine")
elif helmet_status.lower() == "no" and license_status.lower() == "yes" and speed >80:
    print("heavy fine")
else:
    print("moderate fine")
    
#13. Check movie ticket pricing
age = int(input("enter your age:"))
day = input("enter the day of the week:")
membership_availbility = input("do you have a membership card? (yes/no):")
if age<18 and day.lower()=="sunday" and membership_availbility.lower() == "yes":
    print("50% discount")
elif  membership_availbility.lower() == "yes":
    print("25% discount")
else:
    print("no discount")

#14.Check weather alert system
temperature =   int(input("enter the temperature in degree Celsius:"))
wind_speed = int(input("enter the wind speed in km/h:"))
rain_status = input("is it raining? (yes/no):")
if temperature> 40 and wind_speed > 50 and rain_stautus.lower () =="no":
    print("heat alert")
elif wind_speed > 30 and rain_status.lower() == "yes":
    print("storm alert")
else:
    print("normal weather")
    
#15.Check online shopping offer
purchase_amount = float(input("enter your purchase amount in dollars:"))
coupon_availbility = input("do you have a coupon code? (yes/no):")
membership_status = input("are you a member of the loyalty program? (yes/no):")
if purchase_amount >= 10000 and coupon_availbility.lower() == "yes" and membership_status.lower() == "yes":
    print("maximum discount")
elif purchase_amount >= 5000 and coupon_availbility.lower() == "yes":
    print("medium discount")
else:
    print("no discount")

#16. Check server room access
idcard_status       = input("do you have a valid ID card? (yes/no):")
fingerprint_status  = input("is fingerprint recognition available? (yes/no):")
access_level = int(input("enter your access level (1-10):"))
if idcard_status.lower() == "yes" and fingerprint_status.lower() == "yes" and access_level > 5:
    print("access granted")
else:
    print("access restricted")
    
#17.Check sports team selection
speed_score = int(input("enter your speed score:"))
fitness_score =     int(input("enter your fitness score:"))
discipline_score = int(input("enter your discipline score:"))
if speed_score >= 80 and fitness_score >= 80 and discipline_score >= 80:
    print("selected")
elif speed_score >= 60 and fitness_score >= 60 and discipline_score >= 60:
    print("waiting list")
else:
    print("not selected")

#18. Check laptop purchase recommendation
budget = float(input("enter your budget in dollars:"))
storage =   int (input("enter your storage requirement in GB:"))
ram = int(input("enter the required RAM in GB:"))       
if ( budget >= 100000 and ram>= 16 and storage >= 512):
    print("gaming laptop")
elif (budget >= 50000 and ram >= 8 and storage >= 256):
    print("office laptop")
else:
    print("basic laptop")
    
#19. Check bank loan approval
# salary =    int(input("enter your salary:"))
credit_score =  int(input("enter your credit score:"))
experiance  = int(input("enter your years of experience:"))
if salary >= 50000 and credit_score >= 750 and experiance >= 3:
    print("loan approved")
else : 
    print("loan rejected")

#20.Check smart home security system'''
door_status = input("is the door closed? (yes/no):")
camera_status = input("is the security camera active? (yes/no):")
alarm_status  = input("is the alarm system armed? (yes/no):")
if door_status.lower() == "yes" and camera_status.lower() == "yes" and alarm_status.lower() == "yes":
    print("home is secure")
else:
    print("home security compromised")