# Hackathon
Troubled fish game
from typing_extensions import TypeAliasType

print("Hello there Welcome to the Troubled Fish")
Q1 = input("What would you like? 'ube icecream' 'Che Thai' 'mango pudding' 'nothing'")
if Q1 == "ube icecream":
    A1 = input("where is ube icecream origanted from?'Philippines' or 'China'")
    if A1 == "China":
      print("incorrect! No icecream for you Thanks for coming pls come again soon")
    elif A1 == "Philippines":
      print("correct! Here is your ube icecream! Thanks for coming pls come again soon")
if Q1 == "Che Thai":
  A2 = input("Name one ingredient in Che Thai. 'Coconut Milk' or 'jello'")
  if A2 == "Coconut Milk":
    print("This must be your go-to desert. Here is your Che Thai! thanks for coming")
  elif A2 == "jello":
    print("Incorrect! No Chè Thái for you Thanks for coming pls come again soon")
if Q1 == "mango pudding":
  A3 = input("What is the method of cooking for mango pudding? 'boil''baking' 'pan'")
  if A3 == "boil":
    print("Great Knowledge of Cooking! Here is your mango pudding!")
  elif A3 == "baking" or A3 == "pan":
    print("Go practice cooking! No mango pudding for you")
  else:
    print("thanks for coming please come by again!") 
if Q1 == "nothing":
  print("ok, then thanks for coming by!")
