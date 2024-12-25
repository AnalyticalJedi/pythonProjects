# Count Occurrence of Numbers

## Description
This Python program reads a single line of integers from the user (separated by spaces), counts the occurrences of each unique number within the range 1–100, and displays the results. Any numbers outside this range are ignored.

---

## Author: Cherry

---

## Date: November 3, 2024

---

## Functions Used

### `get_user_input()`
- Prompts the user to enter a line of integers separated by spaces.
- Returns the input as a list of integers.

### `count_occurrences(numbers)`
- Filters numbers between 1 and 100 from the input.
- Counts the occurrences of each valid number.
- Returns a dictionary where keys are numbers and values are their respective counts.

### `display_counts(count_dict)`
- Displays the unique numbers and their counts in ascending order.
- Formats the output to indicate whether each number occurs once or multiple times.

---

## Features

- Filters integers between 1 and 100.
- Ignores values outside the specified range.
- Provides a user-friendly display of unique numbers and their occurrences.

---

## How to Run

1. Clone the repository and navigate to the directory containing the file:
   ```bash
   git clone https://github.com/your-username/pythonProjects.git
   cd pythonProjects
   ```

2. Run the script:
   ```bash
   python count_occurrence.py
   ```

---

## Example Input and Output

### Input:
```
Enter integers between 1 and 100, separated by spaces: 5 7 5 100 23 5
```

### Output:
```
5 occurs 3 times
7 occurs 1 time
23 occurs 1 time
100 occurs 1 time
```

---

## Skills Demonstrated

- User input handling.
- Data filtering with conditions.
- Dictionary operations for counting occurrences.
- Formatted output using string manipulation.

---

## Tags

- #Python
- #NumberCounting
- #DataProcessing
- #ProgrammingAssignment
