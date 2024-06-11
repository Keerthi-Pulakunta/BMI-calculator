# BMI-calculator
name=input("name:")
height=float(input("height:"))
weight=int(input("weight:"))

BMI=(weight/height**2)
if BMI<18.5:
    print("you are underweight ")
elif(BMI>18.5 or  BMI<24.9):
    print("you are Healthy")
else:
    print("you are Overweight")

print(f"Ok, {name} you are healthy with the BMI of {BMI}")
