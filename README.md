# Assignment 4

## Description

Assignment 4 will demonstrate my ability of using and handling exceptions.

## Author

Muhammad Rahmani

## pixell_transaction_report.py

I will be using exception handling and making sure that all the programs
are accurate and correct as a software development manager.

## Code Modification 1

If the file is not found, try-except block will catch it and print
the file not found message.

## Code Modification 2

The transaction type and amount are validated if they are invalid, they are
added to the invalid_transactions tuple, and then that tuple is added to
the rejected_transactions list.

## Code Modification 3

Removed transaction_counter. Separated the deposit and withdraw if/elif
statements from customer_id not in customer_data if statement, which
now allows for the transaction_count, balance and average_transaction_amount
to be displayed and calculated correctly.

## Code Modifcation 4

Changed the if statement if transaction_type == "withdrawal", to transaction_type == "withdraw,
since withdraw is the correct transaction_type.


## Code Modification 5

Under withdraw if statement, changed the customer balance += transaction_amount to
balance -= transaction_amount and changed total_transaction_amount += transaction_amount
to total_transaction_amount -= transaction_amount.
The purpose of doing this is to have withdraw substract from customer_balance and from
total_transaction amount.

## Code Modification 6

Formatted customer balance and average transaction amount to 2 decimal places.