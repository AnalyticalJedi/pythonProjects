
# Grade Calculator

## Description
This Python program simulates a grade calculator that determines a letter grade based on a user-provided exam score. The program includes input validation to ensure the score is within the range of 0 to 100 and uses conditional statements to assign grades according to predefined criteria.

---

## Date: September 22, 2024

## Author: Cherry

---

## Features

### Input Validation
- Ensures the user provides a numeric value between 0 and 100.
- Rejects invalid input (e.g., non-numeric values or numbers outside the allowed range) and prompts the user to re-enter the score.

### Grade Assignment Criteria
| **Score Range** | **Grade** |
|------------------|-----------|
| 90 - 100        | A         |
| 80 - 89         | B         |
| 70 - 79         | C         |
| 60 - 69         | D         |
| Below 60        | F         |

### Output
- Displays the letter grade based on the validated exam score.

---

## How to Run

1. Clone the repository and navigate to the directory containing the file:
   ```bash
   git clone https://github.com/your-username/pythonProjects.git
   cd pythonProjects
   ```

2. Run the script:
   ```bash
   python grade_calculator.py
   ```

3. Follow the on-screen instructions to input an exam score.

---

## Example Input and Output

### Input:
```
What is your exam score? 85
```

### Output:
```
Your grade is B
```

### Input with Invalid Values:
```
What is your exam score? -10
Invalid input! Exam score cannot be below 0.
What is your exam score? 105
Invalid input! Exam score cannot be above 100.
What is your exam score? abc
Invalid input. Please enter a NUMBER between 0 and 100.
What is your exam score? 95
Your grade is A
```

---

## Skills Demonstrated

- Input validation for user-provided data.
- Conditional statements to evaluate and categorize data.
- Error handling for invalid input types.
- Basic user interaction in command-line applications.

---

## Tags

- #Python
- #GradeCalculator
- #InputValidation
- #ProgrammingAssignment
