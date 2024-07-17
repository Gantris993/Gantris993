name = "Ground Shipping"
print(name)
weight = 41.5 #lb
print(weight)
flat_charge = "$20" #$
print(flat_charge)
if weight <= 2:
  print("$1.50")
elif weight <= 6:
  print("$3.00")
elif weight <= 10:
  print("$4.00")
else:
  print("$4.75")
cost_ground = (weight * 4.00) + 20
print(cost_ground)

cost_ground_premium = 125.00
print("Ground Shipping Premium $", cost_ground_premium)

name = "Drone Shipping"
print(name)
weight = 41.5 #lb
print(weight)
flat_charge = "$0.00" #$
print(flat_charge)
if weight <= 2:
  print("$4.50")
elif weight <= 6:
  print("$9.00")
elif weight <= 10:
  print("$12.00")
else:
  print("$14.25")
  
cost_drone = (weight * 4.50) + 0.00
print(cost_drone)
