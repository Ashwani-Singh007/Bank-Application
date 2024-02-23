## Bank Application
# Scenario: You are back-end developer and need to create an application to handle new customer bank account requests.
# What is needed to be done:
1. Read a .csv file of names, social security numbers, account type, and initial deposit.
2. Use a proper data structure to hold all these accounts.
3. Both savings and checking share the following properties: deposit(), withdraw(), transfer(), showInfo().<br>
 11-Digit Account Number (generated with the following process: 1 or 2 depending on savings or checking, last two digits of SSN, Unique 5-digit number, and random 3-digit number).
5. Savings Account holders are given a Safety Deposit Box, identified by a 3-digit number and accessed with a 4-digit code.
6. Checking Account holders are assigned a Debit Card with a 12-digit number and a 4-digit PIN.
7. Both accounts will use an interface that determines the base interest rate.
 *Saving accounts will use 0.25 points less than the Base Rate. 
*Checking accounts will use 15% of the Base Rate.
10. The showInfo should reveal relevant account information as well as information specific to the checking account or savings account.<br>
# Learning Objectives:
* Learn to develop robust application architecture.
* Use when to use abstract classes and abstract methods.
* Use an Interface API to receive an information from developer application.
* Explore constructors deeper and use the super() keyword.
* Explore the access modifiers and when to use public, private, or protected.
* Read data from a file and store in an appropriate data structure.
* Generate random numbers and work with String API.
