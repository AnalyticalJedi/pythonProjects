# integer_reading

## Description
This Python program reads an integer between **0** and **1000**, extracts its digits, calculates their sum, and displays the result. The program ensures that the input is within the valid range and provides feedback for invalid inputs.

---

## Author: Cherry

---

## Features

### Input Validation
- Ensures the user provides an integer within the range [0, 1000].
- Rejects inputs outside the valid range and prompts the user to re-enter.

### Digit Extraction and Summation
- Extracts digits from the integer using modular arithmetic.
- Adds the digits iteratively to compute the sum.

### Output
- Displays the total sum of the digits.

---

## How to Run

1. Clone the repository and navigate to the directory containing the file:
   ```bash
   git clone https://github.com/your-username/pythonProjects.git
   cd pythonProjects
   ```

2. Run the script:
   ```bash
   python sum_digits.py
   ```

3. Follow the on-screen instructions to input an integer.

---

## Example Input and Output

### Input:
```
Enter an integer between 0 and 1000: 932
```

### Output:
```
The sum of digits is: 14
```

### Input with Invalid Values:
```
Enter an integer between 0 and 1000: 1500
Please enter a number between 0 and 1000.
Enter an integer between 0 and 1000: 87
The sum of digits is: 15
```

---

## Skills Demonstrated

- Input validation for user-provided data.
- Modular arithmetic for digit extraction.
- Looping structures for iterative calculations.
- User-friendly error handling and messaging.

---

## Tags

- #Python
- #DigitSum
- #InputValidation
- #ProgrammingAssignment
