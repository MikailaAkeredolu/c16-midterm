# Leverage the UML to answer the questions below
> Assume getters, setters and toString where needed. See beloe for the requirements:

- Your Bank must be able to add customers and keep a list of them
- Every account created must have a uqique accountNumber
- You should also be able to track the number sof accounts created
- Customers can make deposits and withdrawals
- Customers cannot deposit negative values if they do print an message such as ***Invalid amount***
- If a customer tries to withdraw more than their balance plus fees then  print an message such as ***Insufficient Funds***
- IMPORTANT:
  - Accounts with balances over $1000 recieve a 10% intetrest added to their balance when they make a deposit while accounts with less that $1000 get a 5% interest added to their balance when they make a deposit
  -  There is a withdrawal transactionFee of  $5 for all checking accounts
  -  There is withdrawal  transactionFee of  $10 for all savings accounts

<img width="855" alt="Screenshot 2024-10-17 at 9 59 50 AM" src="https://github.com/user-attachments/assets/6853df8e-cd42-4f52-9da5-6f1ed78292b6">



> Inside the main method, do the following:

- Part 1

  -  Createa a bank account object
  -  Createa a checking account named checkingAccount1
  -  Createa a customer account instance named customer1
  -  add customer1 to the link of the bank's cuntomers
  -  deposit $2000 into customer1's checking account
  -  withdraw $100 from customer1's checking account
  -  withdraw another $50 from customer1's checking account
  -  deposit $60 into customer1's checking account
  -  attempt to deposit a negative value
 
   
- Part 2

  -   Createa a savings account named savings
  -   Createa a customer account instance named customer2
  -   add customer1 to the link of the bank's cuntomers
  -   deposit $500 into customer2's savings account
  -   attempt to withdraw $1 million from the account
  -   withdraw $100 from customer2's savings account


- Part 3

  -  Createa a checking account named checkingAccount2
  -  Createa a customer account instance named customer3
  -  add customer3 to the link of the bank's cuntomers
  -  deposit $1000 into customer1's checking account
  -  withdraw $100 from customer1's checking account


- Part 4

 Invoke printAllCustomers method to display their info as seen below

    - Sample Expected output:

    ```
        Account Type: Checking Account
        Account Number: 1
        Balance: $2106.00  
    
    
        Account Type: Savings Account
        Account Number: 2
        Balance: $415.00  
    
        Account Type: Checking Account
        Account Number: 3
        Balance: $1050.00  
    ```


- Part 5

 - Print the total number of customers in the bank

   - Sample Expected output
      ```
      3
    ```
