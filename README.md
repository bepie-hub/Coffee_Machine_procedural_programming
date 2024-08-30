This program simulates a coffee machine that allows the user to purchase various coffee drinks (espresso, latte, cappuccino). The program monitors resources (water, milk, coffee) and earned money.

Main functions:

- check_resources(key_list):
Checks if the available resources (water, milk, coffee) are sufficient to prepare selected drink. If there are not enough resources, the program shows a message about the lack of resources.

- process_coins(): 
Handles the user's coin insertion process and checks whether the entered amount is sufficient to purchase selected drink. If the amount is bigger than the price of the drink, it returns the change. If the amount is insufficient, it returns the coins to the user.

The program works in a loop, asking the user what he would like to drink: espresso, latte, cappuccino, or turn off the machine (off). Entering 'report' displays the current state of resources (water, milk, coffee) and earned money. The program processes the user's selection, checks the resources, processes the coins and performs the appropriate operations.

Usage example: 
the program asks the user to choose a drink: “What would you like to drink? (espresso/latte/cappuccino):”. If the user selects “espresso,” the program will check if enough water and coffee are available. The user will be asked to determine number of coins (quarter, dime, nickel, penny). If the amount is sufficient, the program will prepare the coffee, give the change (if needed) and update level of the resources. The process works till the user enters 'off'(break the loop).
