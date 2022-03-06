# Shawn Hing Tip_Calculator.py Project1
# A little humor lol
print("Don't forget to make a donation to the Shawn Hing Fund")

# Input the cost
cost_of_food = float(input("What is the cost of the food?: "))

# Input the tip
tip_percentage = int(input("What percent tip?: "))

# Input the number of people
number_of_people_paying = int(input("How many people are splitting bill? "))

# Create new line
print("\n")

# How much each person pays for cost of food and tip
payment_per_person = ("%.2f" % round(float(((tip_percentage / 100 +1) * cost_of_food) / number_of_people_paying), 2))

# Print the tip amount 
tip_percentage = "%.2f" % float(tip_percentage / 100 * cost_of_food)
print(f"Tip amount: ${tip_percentage}")

# Change cost of food and percentage of tip to floats so they can be added up
cost_of_food_float = float(cost_of_food)
tip_percentage_float = float(tip_percentage)
tip_percentage_and_cost_of_food = (cost_of_food_float + tip_percentage_float)
print(f"cost of food including percentage of tip: ${tip_percentage_and_cost_of_food}")

# Print how much each person pays
print(f"Each person pays: ${payment_per_person}")

# Humor continues lol!
print("Don't forget to make a donation to the Shawn Hing Fund!")


