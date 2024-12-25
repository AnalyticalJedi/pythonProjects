# Bank Account Simulator

## Description
This Python program simulates a bank account, allowing users to:

- Set up an account with an ID, balance, and annual interest rate.
- Perform transactions like deposits and withdrawals.
- Calculate the monthly interest rate and amount.

The program is implemented using a class-based design with private attributes and accessor/mutator methods for secure and modular handling of account data.

---

## Date of Completion
**November 18, 2024**

## Author: Cherry

---

## Features

- **Account Management**: Create an account with a unique ID, balance, and annual interest rate.
- **Transaction Support**:
  - Deposit funds.
  - Withdraw funds (with balance validation).
- **Interest Calculation**:
  - Compute monthly interest rate.
  - Calculate monthly interest amount based on current balance.
- **Encapsulation**: Uses private attributes to ensure secure data management.

---

## Class Design

### Attributes
- **`id`**: Integer representing the account ID.
- **`balance`**: Float for the account balance.
- **`annualInterestRate`**: Float for the annual interest rate (percentage).

### Methods

| **Method**                        | **Description**                                          |
|-----------------------------------|----------------------------------------------------------|
| `__init__(self, id, balance, annualInterestRate)` | Initializes the account with default or specified values. |
| `get_id(self), set_id(self, id)`  | Accessor and mutator for the account ID.                |
| `get_balance(self), set_balance(self, balance)`  | Accessor and mutator for the account balance.          |
| `get_annualInterestRate(self), set_annualInterestRate(self, annualInterestRate)` | Accessor and mutator for the annual interest rate. |
| `getMonthlyInterestRate(self)`    | Returns the monthly interest rate.                     |
| `getMonthlyInterest(self)`        | Returns the monthly interest amount.                   |
| `withdraw(self, amount)`          | Deducts the specified amount from the balance.         |
| `deposit(self, amount)`           | Adds the specified amount to the balance.              |

---

## How to Run

1. Clone the repository and navigate to the directory containing the file:
   ```bash
   git clone https://github.com/your-username/pythonProjects.git
   cd pythonProjects
   ```

2. Run the script:
   ```bash
   python annual_interest_rate.py
   ```

---

## Example Input and Output

### Input:
- Account ID: `1122`
- Initial Balance: `$20,000`
- Annual Interest Rate: `4.5%`
- Withdrawal: `$2,500`
- Deposit: `$3,000`

### Output:
```
Account ID: 1122
Balance: 20500.0
Monthly Interest Rate: 0.375
Monthly Interest: 76.875
```

---

## Skills Demonstrated

- Class-based programming with Python.
- Use of accessor (`get`) and mutator (`set`) methods for secure data handling.
- Encapsulation and private attributes.
- Calculation of percentages and rates.
- Input validation and error handling.

---

## Tags

- #Python
- #BankAccount
- #Encapsulation
- #InterestCalculation
- #ProgrammingAssignment
