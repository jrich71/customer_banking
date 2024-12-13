# Module 3 Challenge

## Purpose

For this assignment, I created a simple customer banking system that, according to the class website:

>allows users to calculate and track interest earned on savings and CD accounts. By running this application, users will be able to enter their savings and CD account information, see the interest earned, and view the updated balances after a specified number of months.

## Files

Four python files comprise the system code:

* Accounts.py: This file holds the "Accounts" class and instantiates its related paramters, along with two methods for setting the savings and cd account values

* savings_account.py: This file defines the function "create_savings_account" that allows a user to create a count, set a savings account value, and set a savings account interest rate. Of note, the following formula is used to calculate the value of interest accrued given a time (months) and the balance:

  > balance: \* (interest_rate/100) \* (months/12)

* cd_account.py: This file defines the function "create_cd_account" that allows a user to create a count, set a cd account value, and set a cd account interest rate. Of note, the following formula is used to calculate the value of interest accrued given a time (months) and the balance (same as above):

  > balance: \* (interest_rate/100) \* (months/12)

* customer_banking.py: This file enables users to enter their information to create savings and cd accounts, update the balances with earned interest, and return/display the updated balances with interest.
