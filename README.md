# tip_calc
Tip Calculator

#print("Welcome to the tip calculator.")

#VARIABLES:
bill = (input("What was the total bill? $"))
tip = input("How much tip would you like to give? 10, 12, or 15? ")
num_guest = input("How many people to split the bill? ")

#EQUATION VARIABLES:
bill_as_int = int(bill)
tip_as_int = int(tip)
num_guest_as_int = int(num_guest)
tip_factor = 1+(tip_as_int/100)
bill_with_tip = (bill_as_int*tip_factor)

each_pay = bill_with_tip/num_guest_as_int
print("Pay this amount each: "+str(round(each_pay),2))
print("hello world"
