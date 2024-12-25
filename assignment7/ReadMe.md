# Extended String Manipulation (MyString)

## Description
The `MyString` class extends Python's built-in `str` class to provide additional functionality for finding the **first** and **last** occurrence of a character within a string. This class introduces two new methods, `indexOf` and `lastIndexOf`, which allow for efficient character searches within strings.

---

## Date of Completion
**November 23, 2024**

## Author
**Cherry**

---

## Features

### Methods

1. **`indexOf(self, ch, fromIndex)`**
   - Finds the index of the **first** occurrence of a character (`ch`) starting from a given index (`fromIndex`).
   - Returns `-1` if the character is not found.

2. **`lastIndexOf(self, ch, fromIndex)`**
   - Finds the index of the **last** occurrence of a character (`ch`) before or at a given index (`fromIndex`).
   - Returns `-1` if the character is not found.

### Parameters
- **`ch`**: The character to search for in the string.
- **`fromIndex`**: The starting or ending index for the search.

### Input
- A `MyString` instance and the character(s) to search for.
- Starting or ending index for the search.

### Output
- The index of the first or last occurrence of the character if found.
- `-1` if the character is not found within the specified range.

---

## How to Run

1. Clone the repository and navigate to the directory containing the file:
   ```bash
   git clone https://github.com/your-username/pythonProjects.git
   cd pythonProjects
   ```

2. Run the script:
   ```bash
   python first_last_occurrence.py
   ```

---

## Example Input and Output

### Input:
String: `Programming is fun. Programming is fun.`
Character: `'i'`

### Output:
```
12
28
28
-1
```
Explanation:
- `12`: The first occurrence of `'i'` after index 10.
- `28`: The first occurrence of `'i'` after index 23.
- `28`: The last occurrence of `'i'` before or at index 29.
- `-1`: No occurrence of `'i'` before or at index 4.

---

## Skills Demonstrated

- Class inheritance in Python.
- Method overriding for extending functionality.
- Exception handling with `try` and `except`.
- String manipulation using `index` and `rfind` methods.

---

## Tags

- #Python
- #StringManipulation
- #ClassInheritance
- #ProgrammingAssignment
