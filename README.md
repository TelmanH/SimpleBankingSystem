# SimpleBankingSystem
Second project

This is a simple banking system project. SqLite3 is used for the data storing of this application. Additionally, Luhn algoritm is used for credit card number identification.

In order to run this project bankingmain.py file should be executed.
After execution user is prompted with a menu as follows:
1.Create an account
2.Log into account
0.Exit
System takes appropriate input from the user and displayes the output according to the menu.
When user chooses the create an account option, system creates an account for the user. It also assigns a credit card and PIN code for the credit card. Credit card number is unique 
and calculated by using Luhn algorithm. 
When user chooses Log into account option, system asks for a credit card number and PIN. If credit card number or PIN is not correct, user is propmted with a message. After logging
into the account, user can perform the following operations:
1.Check balance
2.Add income
3.Do transfer
4.Close account
5.Log out
0.Exit
When user selects option 1, system queries the database for the user balance with corresponding credit card nubmer.
When option 2 is selected, user can add balance to the account. Account update is reflected on the database.
When option 3 selected, user can transfer balance to another user with the credit card number. 
With option 4, user can delete the account.
When option 5 is selected, user logs out from the system.
Input "0" is used to go back to the previous menu.
