# File Content Counter

## Description
This Python program counts the number of **characters**, **words**, and **lines** in a user-specified file. It reads the contents of the file, processes them, and displays the results. The program handles errors gracefully, informing the user if the specified file does not exist.

---

## Author: Cherry

---

## Date: December 2, 2024

---

## Features

- **Counts File Contents**:
  - Total number of lines.
  - Total number of words.
  - Total number of characters.
- **Error Handling**: Notifies the user if the specified file does not exist.
- **Simple User Interaction**: Prompts the user to input the filename.

---

## Functions Used

### `count_file_contents(filename)`
- **Parameters**:
  - `filename` (str): The name of the file to process.
- **Input**:
  - A valid text file.
- **Output**:
  - Total counts for lines, words, and characters.
- **Error Handling**:
  - Prints an error message if the file is not found.

---

## How to Run

1. Create a text file (e.g., `grocerylist.txt`) and save it in the same directory as the program.
   - Example contents of `grocerylist.txt`:
     ```
     Carrot
     Oatmeal
     Steak
     Potato
     Corn
     Milk
     ```

2. Clone the repository and navigate to the directory containing the file:
   ```bash
   git clone https://github.com/your-username/pythonProjects.git
   cd pythonProjects
   ```

3. Run the script:
   ```bash
   python counter.py
   ```

4. Enter the filename when prompted:
   ```
   Enter the filename: grocerylist.txt
   ```

---

## Example Output

For the file `grocerylist.txt` containing:
```
Carrot
Oatmeal
Steak
Potato
Corn
Milk
```

The program outputs:
```
Number of lines: 6
Number of words: 6
Number of characters: 38
```

---

## Skills Demonstrated

- File handling in Python.
- Reading and processing text files.
- Counting and aggregating data.
- Error handling for file operations.

---

## Tags

- #Python
- #FileProcessing
- #ProgrammingAssignment
- #BeginnerProject
