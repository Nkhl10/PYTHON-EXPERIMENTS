# PYTHON-EXPERIMENTS
EXPERIMENT 1:
Step 1: Create a base Vehicle class to store common vehicle details such as vehicle ID, model, category, and rental rate.
Step 2: Create three different vehicle types: Car, Bike, and Electric Scooter. These inherit the common properties from the Vehicle class.
Step 3: Create a Rental class to manage the rental information, such as the selected vehicle and rental duration.
Step 4: Initialize the required information using the constructor.
Step 5: Use special methods to display and represent the rental objects.
Step 6: Use __len__() to represent rental-related information, such as the rental duration.
Step 7: Use __del__() to demonstrate the deletion of a rental object.
Step 8: Calculate the total rental amount based on the vehicle's rental rate and the number of rental days.
Step 9: Create objects for different vehicle categories such as a car, bike, and electric scooter.
Step 10: Demonstrate inheritance, where the child vehicle classes use the properties and behavior of the base Vehicle class.
Step 11: Demonstrate Python's special methods through object creation, display, length calculation, and deletion.
Step 12: Finally, execute the program and verify the rental details and calculated rental amount.
----------------------------------------------------------------------------------------------------------------------
EXPERIMENT 2:
Step 1: Create a base Bank Account class to store common account details such as account number, customer name, balance, and PIN.
Step 2: Use encapsulation to keep sensitive account information private, especially the account details, balance, and PIN.
Step 3: Create different account types: Savings Account, Current Account, and Fixed Deposit Account.
Step 4: Use inheritance so that the different account types can use the common features of the base Bank Account class.
Step 5: Implement basic banking operations such as depositing and withdrawing money.
Step 6: Implement a method to set and validate the PIN.
Step 7: Implement interest calculation. Each account type has a different interest rate.
Step 8: Demonstrate runtime polymorphism by using the same interest-calculation method for different account types, where each account gives a different result.
Step 9: Implement operator overloading using + to calculate the combined balance of two accounts.
Step 10: Implement another operator, >, to compare the balances of two accounts.
Step 11: Create objects for Savings Account, Current Account, and Fixed Deposit Account and perform transactions.
Step 12: Finally, display the interest, combined balance, and balance comparison to verify encapsulation, inheritance, polymorphism, and operator overloading.

------------------------------------------------------------------------------------------------------------------
EXPERIMENT 3:
1. Create the Vehicle class
   Create a base class named Vehicle to store vehicle ID, model, category, and rental rate.
2. Create Vehicle Subclasses
   Create Car, Bike, and Electric Scooter classes that inherit from the Vehicle class.
3. Create the Rental class
   Create a Rental class to store customer name, selected vehicle, rental days, and additional kilometers.
4. Initialize Objects
   Use the __init__() method to initialize the required details of vehicles and rentals.
5. Implement String Representation
   Use __str__() to display vehicle and rental information in a readable format.
6. Implement Object Representation
   Use __repr__() to provide a detailed representation of the objects.
7. Implement Length Method
   Use __len__() to return the number of rental days.
8. Implement Object Deletion
   Use __del__() to demonstrate deletion of a rental object.
9. Implement Rent Calculation
   Create calculate rent() to calculate the total rental amount based on rental days, additional kilometers, and security deposit.
10. Add SUV Category
    Create an SUV class as an additional vehicle category.
11. Create Vehicle Objects
    Create objects for Car, Bike, Electric Scooter, and SUV.
12. Create a Rental Object
    Assign a vehicle to a customer and specify the rental duration and additional kilometers.
13. Demonstrate Inheritance
    Show that the vehicle subclasses inherit common properties and methods from the Vehicle class.
14. Display Rental Details
    Display the customer, vehicle, rental duration, additional kilometers, and security deposit.
15. Calculate and Verify Rent
    Calculate the final rental amount and verify that the output is correct.
16. Demonstrate Special Methods
    Display the results of __str__(), __repr__(), __len__(), and __del__().
17. Display Final Output
    Show the complete vehicle and rental information along with the calculated rental amount.
