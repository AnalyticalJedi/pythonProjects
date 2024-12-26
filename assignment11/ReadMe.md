# Temperature Conversion Tool

## Description
This Python program provides a simple command-line interface for converting temperatures between **Celsius** and **Fahrenheit**. The user can select their desired conversion type from a menu and input the temperature to be converted.

---

## Date: October 11, 2024
## Author: Cherry
## Features

### Conversion Options
1. **Celsius to Fahrenheit**:
   ```
   Fahrenheit = (Celsius * 9/5) + 32
   ```
2. **Fahrenheit to Celsius**:
   ```
   Celsius = (Fahrenheit - 32) * 5/9
   ```

### User Interaction
- Displays a text-based menu with conversion options.
- Allows the user to select a conversion type or exit the program.
- Validates user input to ensure proper selection.

### Input Validation
- Ensures the user enters a numeric temperature value for conversion.
- Displays error messages for invalid inputs and prompts the user to try again.

---

## How to Run

1. Clone the repository and navigate to the directory containing the file:
   ```bash
   git clone https://github.com/your-username/pythonProjects.git
   cd pythonProjects
   ```

2. Run the script:
   ```bash
   python tempConvTool.py
   ```

3. Follow the on-screen instructions to select a conversion option and enter a temperature value.

---

## Example Input and Output

### Menu Display:
```
Welcome to the Temperature Conversion Tool!
Select the conversion you would like to perform:
1. Convert Celsius to Fahrenheit
2. Convert Fahrenheit to Celsius
3. Exit
```

### Input and Output for Celsius to Fahrenheit:
```
Enter temperature in Celsius: 25
It is 25°C which is 77°F
```

### Input and Output for Fahrenheit to Celsius:
```
Enter temperature in Fahrenheit: 98.6
It is 98.6°F which is 37.0°C
```

### Exiting the Program:
```
Goodbye!
```

---

## Skills Demonstrated

- User input validation and error handling.
- Function design for modular and reusable code.
- Menu-driven command-line interfaces.
- Mathematical operations for temperature conversion.

---

## Tags

- #Python
- #TemperatureConversion
- #CommandLineTool
- #ProgrammingAssignment
