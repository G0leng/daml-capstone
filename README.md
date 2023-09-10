# LendAMoney
This is my capstone project that allows lender to loan money to borrowers. Lender can approve and reject loan application of the borrower.

### Workflow
1. Borrower needs to provide their information and submit it to the lender
2. The lender will evaluate the borrower capacity to pay the loan amount.
3. Lender could approve or reject the loan amount.
4. A loan is rejected when the requested loan amount is greater than the montly salary of the borrower.
5. An interest rate will apply to loan and then minimum monthly installment will be computed.
6. The borrower sould be able to pay atleast the minimum monthly installment set.
7. The borrower will not be able to borrow additional money not unless the balance from the previous loan has been settled.
   
### Compiling and Testing
To compile and test, run
```
$ daml start
```

