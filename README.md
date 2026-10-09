# Moduler & Packager

**Author:** Sneha Padsala

**Project Type:** Moduler & Packager

**Language:** Python 

---

## Table of Contents

1. Project Overview
2. Project Objectives
3. Features
4. Python Modules Used
5. Project Structure
6. Requirements
7. How to Run the Project
8. Main Menu and Output
9. Date and Time Operations
10. Mathematical Operations
11. Random Data Generation
12. UUID Generation
13. File Operations
14. Explore Module Attributes
15. Functions Used in the Project
16. Python Concepts Practiced
17. Error Handling
18. Learning Outcomes
19. Future Improvements
20. Author
21. Conclusion

---

## 1. Project Overview

The Multi-Utility Toolkit is a menu-driven Python application that combines multiple useful operations in a single program.

The application allows users to perform date and time calculations, mathematical calculations, random data generation, UUID generation, file operations, and Python module exploration.

The project uses Python's built-in modules, functions, loops, conditional statements, exception handling, and file handling.

Users can select an option from the main menu and access the required functionality. Each submenu provides additional options for performing specific operations.

This project is developed for learning and practicing Python programming concepts.

### Purpose of the Project

The main purpose of this project is to understand how multiple Python operations can be organized into one application using functions and menus.

It also provides practical experience with Python modules such as `datetime`, `time`, `math`, `random`, `uuid`, and `importlib`.

---

## 2. Project Objectives

The main objectives of this project are:

* To understand Python modules and packages.
* To create and use user-defined functions.
* To develop a menu-driven Python application.
* To perform date and time operations.
* To calculate factorials and compound interest.
* To perform trigonometric calculations.
* To calculate the area of geometric shapes.
* To generate random numbers and lists.
* To generate random passwords and six-digit OTPs.
* To perform random sampling from user-provided data.
* To generate unique identifiers using UUID.
* To create, write, read, and append files.
* To import modules dynamically using `importlib`.
* To explore module attributes using `dir()`.
* To handle invalid input using exception handling.
* To improve problem-solving and programming skills.

---

## 3. Features

### 3.1 Date and Time Operations

This section provides seven menu options, including the return option.

1. Display the current date and time.
2. Calculate the difference between two dates.
3. Format a date into a custom format.
4. Measure elapsed time using a stopwatch.
5. Run a countdown timer.
6. Return to the main menu.

**Modules used:** `datetime` and `time`

### 3.2 Mathematical Operations

This section provides mathematical calculations.

1. Calculate the factorial of a number.
2. Calculate compound interest.
3. Calculate sine, cosine, and tangent.
4. Calculate the area of a circle, rectangle, or triangle.
5. Return to the main menu.

**Module used:** `math`

### 3.3 Random Data Generation

This section provides the following operations.

1. Generate a random number between 1 and 100.
2. Generate a list containing five random numbers.
3. Generate a random password of a specified length.
4. Generate a six-digit OTP.
5. Select random items from a list.
6. Return to the main menu.

**Module used:** `random`

**Security note:** This project's password and OTP generation is for learning purposes. Production applications should use the `secrets` module for security-sensitive random values.

### 3.4 UUID Generation

This section generates a UUID using `uuid.uuid4()`.

The generated identifier is useful for demonstrating unique identifiers in Python.

### 3.5 File Operations

The File Operations menu provides four operations.

1. Create a new file.
2. Write data into a file.
3. Read data from a file.
4. Append data to a file.
5. Return to the main menu.

### 3.6 Explore Module Attributes

This section allows users to enter a module name and explore its attributes.

It uses `importlib.import_module()` to import the specified module dynamically and `dir()` to display the names available in that module.

Example module names:

* `math`
* `random`
* `datetime`
* `time`

---

## 4. Python Modules Used

| Module      | Purpose                                                              |
| ----------- | -------------------------------------------------------------------- |
| `datetime`  | Displaying dates, formatting dates, and calculating date differences |
| `time`      | Measuring elapsed time and running a countdown                       |
| `math`      | Factorial, trigonometry, radians, and mathematical constants         |
| `random`    | Random numbers, lists, passwords, OTPs, and sampling                 |
| `uuid`      | Generating UUID identifiers                                          |
| `importlib` | Importing modules dynamically                                        |

### Custom Modules

The main Python file also imports these custom modules:

* `custom_modules.file_operations`
* `custom_modules.math_operations`

These imports demonstrate how a Python program can import modules created by the programmer.

In the supplied code, the main menu's file and mathematical operations are implemented directly in the main file. The imported custom-module functions are not called by these menu functions.

---

## 5. Project Structure

The following is a suggested project structure.

```text
Moduler&Packager
│
├── custom_modules/
│   ├── __init__.py
│   ├── file_operations.py
│   └── math_operations.py
│
└── README.md
```

### File Descriptions

**`main.py`**

Contains the main program, menus, functions, and program execution logic.

**`custom_modules/`**

Contains the custom Python modules.

**`__init__.py`**

Can be used to mark the custom modules directory as a regular Python package.

**`file_operations.py`**

Intended for functions related to file handling.

**`math_operations.py`**

Intended for custom mathematical functions.

**`README.md`**

Contains project documentation, features, instructions, and sample outputs.

The filenames and folder structure should match the actual files in your project.

---

## 6. Requirements

The following requirements are needed to run this project:

* Python 3.x
* Visual Studio Code or another Python editor
* Windows Command Prompt or a terminal
* The project files and required custom package

The standard library modules used in the supplied code do not require separate installation.

The `custom_modules` package must also be available because the program imports it at startup.

---

## 7. How to Run the Project

### Step 1: Install Python

Download Python from the official website:

https://www.python.org/downloads/

### Step 2: Open Visual Studio Code

Open Visual Studio Code and select the project folder.

### Step 3: Check the Project Files

Ensure that your main Python file and `custom_modules` directory are present.

### Step 4: Open the Terminal

In Visual Studio Code, select:

**Terminal → New Terminal**

### Step 5: Run the Program

If the main file is named `main.py`, enter:

```bash
py Moduler & Packager .py
```

If your file has a different name, replace `main.py` with the actual filename.

### Step 6: Select an Operation

The main menu will appear. Enter a number from `1` to `7` to access an operation or exit the program.

---

## 8. Main Menu and Output

### Main Menu

The program displays the following menu:

```text
==============================
Welcome to Multi-Utility Toolkit
==============================
Choose an option:
1. Datetime and Time Operations
2. Mathematical Operations
3. Random Data Generation
4. Generate Unique Identifiers (UUID)
5. File Operations (Custom Module)
6. Explore Module Attributes (dir())
7. Exit
Enter your choice:
```

### Example: Selecting Option 1

**Input:**

```text
Enter your choice: 1
```

**Output:**

```text
--- Datetime and Time Operations ---
1.Display current date and time
2.Calculate the difference between two dates/times
3.Format date into custom format
4.Stopwatch
5.countdown timer
6.Back to main menu
Enter your choice (1-6):
```

### Example: Selecting Option 7

**Input:**

```text
Enter your choice: 7
```

**Output:**

```text
==============================

Thank you for using the Multi-Utility Toolkit!
==============================
```

The program terminates after displaying the thank-you message.

---

## 9. Date and Time Operations

This section uses the `datetime` and `time` modules.

### 9.1 Display Current Date and Time

**Purpose:** Displays the current date and time of the computer.

**Function used:** `datetime.datetime.now()`

**Input:**

```text
Enter your choice (1-6): 1
```

**Example output:**

```text
--- Datetime and Time Operations ---
1.Display current date and time
2.Calculate the difference between two dates/times
3.Format date into custom format
4.Stopwatch
5.countdown timer
6.Back to main menu
Enter your choice (1-6): 1

Current date and time: 2026-10-09 16:20:00.123456
================================
```

The displayed date and time are illustrative; actual values depend on the computer's clock.

### 9.2 Calculate the Difference Between Two Dates

**Purpose:** Calculates the absolute difference between two dates.

The program accepts dates in `YYYY-MM-DD` format.

**Example input:**

```text
Enter your choice (1-6): 2
Enter the first date (YYYY-MM-DD): 2026-10-01
Enter the second date (YYYY-MM-DD): 2026-10-09
```

**Output:**

```text
Difference : 8 days, 0:00:00
```

The `abs()` function ensures that the difference is non-negative, regardless of the order of the entered dates.

**Invalid input example:**

```text
Enter the first date (YYYY-MM-DD): 10-01-2026
Enter the second date (YYYY-MM-DD): 2026-10-09
Invalid date format. Please enter date in the format YYYY-MM-DD.
```

### 9.3 Format Date into a Custom Format

**Purpose:** Converts an entered date into a different display format and shows its weekday and month name.

**Input:**

```text
Enter your choice (1-6): 3
Enter format date custom formate (YYYY-MM-DD): 2026-10-09
```

**Output:**

```text
Formatted date: 09-10-26
Days: Friday
Month: October
```

**Functions used:**

* `strptime()` converts the entered date string into a date object.
* `strftime()` formats the date into the required representation.

The format `%d-%m-%y` displays the day, month, and two-digit year.

### 9.4 Stopwatch

**Purpose:** Measures the elapsed time between starting and stopping the stopwatch.

**Input:**

```text
Enter your choice (1-6): 4
```

**Example output:**

```text
Stopwatch started.
Press Enter to stop stopwatch...
Elapsed time: 3.42 seconds
```

The elapsed time depends on how long the user waits before pressing Enter.

**Function used:** `time.perf_counter()`

This function is suitable for measuring elapsed time.

### 9.5 Countdown Timer

**Purpose:** Counts down from a user-specified number of seconds.

**Input:**

```text
Enter your choice (1-6): 5
Enter countdown time in seconds: 3
```

**Example output:**

```text
Time remaining: 1 seconds
Time's up!
```

The countdown updates the same terminal line using `end="\r"`. Therefore, the intermediate numbers may overwrite one another instead of appearing on separate lines.

**Function used:** `time.sleep(1)`

**Invalid input example:**

```text
Enter countdown time in seconds: abc
Invalid input. Please enter a valid number.
```

**Negative input example:**

```text
Enter countdown time in seconds: -5
Please enter a positive number.
```

### 9.6 Return to Main Menu

**Input:**

```text
Enter your choice (1-6): 6
```

The `break` statement exits the date and time menu loop and returns control to the main menu.

---

## 10. Mathematical Operations

This section uses the `math` module and user-defined functions.

### Mathematical Menu

```text
Mathematical Operations Menu:
1.calculate factorial
2.solve compound interest
3.Trigonometric calculations
4.area of geometric shapes
5.Back to main menu
Enter your choice (1-5):
```

### 10.1 Calculate Factorial

**Purpose:** Calculates the factorial of an integer.

The factorial of a non-negative integer is the product of all positive integers up to that number.

For example:

\(5! = 5 \times 4 \times 3 \times 2 \times 1 = 120\)

**Input:**

```text
Enter your choice (1-5): 1
Enter a number: 5
```

**Output:**

```text
Factorial: 120
```

**Function used:** `math.factorial(num)`

**Invalid input example:**

```text
Enter a number: abc
invalid literal for int() with base 10: 'abc'
```

A negative integer also causes an error from `math.factorial()`, which is displayed by the exception handler.

### 10.2 Calculate Compound Interest

**Purpose:** Calculates compound interest using the principal amount, annual interest rate, and time in years.

The formula used by the code is:

$$
A = P(1 + r/100)^t
$$

$$
CI = A - P
$$

Where:

* \(P\) = Principal amount
* \(r\) = Annual interest rate in percent
* \(t\) = Time in years
* \(A\) = Final amount
* \(CI\) = Compound interest

**Input:**

```text
Enter your choice (1-5): 2
Enter principal amount: 10000
Enter rate of interest (in %): 5
Enter time (in years): 2
```

**Output:**

```text
Compound Interest: 1025.00
```

The function returns the interest earned, not the final amount.

**Invalid input example:**

```text
Enter principal amount: abc
Please enter valid numbers.
```

### 10.3 Trigonometric Calculations

**Purpose:** Calculates sine, cosine, and tangent for an angle entered in degrees.

**Input:**

```text
Enter your choice (1-5): 3
Enter angle in degrees: 30
```

**Output:**

```text
sin(30.0) = 0.5000
cos(30.0) = 0.8660
tan(30.0) = 0.5774
```

**Functions used:**

* `math.radians()` converts degrees to radians.
* `math.sin()` calculates sine.
* `math.cos()` calculates cosine.
* `math.tan()` calculates tangent.

The program displays each result rounded to four decimal places.

### 10.4 Area of Geometric Shapes

**Purpose:** Calculates the area of a circle, rectangle, or triangle.

**Submenu:**

```text
1. Circle
2. Rectangle
3. Triangle
Choose shape:
```

#### A. Circle

Formula:

$$
Area = \pi r^2
$$

**Input:**

```text
Choose shape: 1
Enter radius: 5
```

**Output:**

```text
Area of Circle: 78.53981633974483
```

**Function:** `circle_area(radius)`

#### B. Rectangle

Formula:

$$
Area = length \times width
$$

**Input:**

```text
Choose shape: 2
Enter length: 10
Enter width: 5
```

**Output:**

```text
Area of Rectangle: 50.0
```

**Function:** `rectangle_area(length, width)`

#### C. Triangle

Formula:

$$
Area = \frac{1}{2} \times base \times height
$$

**Input:**

```text
Choose shape: 3
Enter base: 10
Enter height: 6
```

**Output:**

```text
Area of Triangle: 30.0
```

**Function:** `triangle_area(base, height)`

**Invalid shape example:**

```text
Choose shape: 4
Invalid shape.
```

**Invalid numeric input example:**

```text
Enter radius: abc
Please enter valid numbers.
```

### 10.5 Return to Main Menu

**Input:**

```text
Enter your choice (1-5): 5
```

The `break` statement exits the mathematical menu loop.

---

## 11. Random Data Generation

This section uses Python's `random` module.

### Random Menu

```text
--- Random Data Generation ---
1. Generate Random Number
2. Generate Random List
3. Create Random Password
4. Generate Random OTP
5. Random Sampling
6. Back to Main Menu
Enter your choice:
```

### 11.1 Generate Random Number

**Purpose:** Generates one random integer between 1 and 100.

**Input:**

```text
Enter your choice: 1
```

**Example output:**

```text
Random Number: 47
```

The number can be different each time.

**Function used:** `random.randint(1, 100)`

### 11.2 Generate Random List

**Purpose:** Generates a list of five random integers between 1 and 100.

**Input:**

```text
Enter your choice: 2
```

**Example output:**

```text
Random List: [12, 87, 45, 3, 69]
```

The list values are examples. The program generates new values when the option is selected.

### 11.3 Create Random Password

**Purpose:** Generates a password using lowercase letters, uppercase letters, digits, and special characters.

The user chooses the password length.

**Input:**

```text
Enter your choice: 3
Enter password length: 8
```

**Example output:**

```text
Generated Password: aB7@kP2!
```

The generated password will vary each time.

**Invalid length example:**

```text
Enter password length: 0
Length must be greater than 0.
```

**Invalid input example:**

```text
Enter password length: abc
Please enter a valid length.
```

### 11.4 Generate Random OTP

**Purpose:** Generates a six-digit integer between 100000 and 999999.

**Input:**

```text
Enter your choice: 4
```

**Example output:**

```text
Generated OTP: 583194
```

The OTP is randomly generated and may change each time.

**Note:** The current implementation is intended for demonstration. Use `secrets` for security-sensitive OTP generation.

### 11.5 Random Sampling

**Purpose:** Selects a specified number of unique items from a list entered by the user.

**Input:**

```text
Enter your choice: 5
Enter items separated by commas: apple, banana, mango, orange
How many items to sample? 2
```

**Example output:**

```text
Random Sample: ['mango', 'apple']
```

The selected items and their order may change.

**Invalid sample size example:**

```text
Enter items separated by commas: apple, banana, mango
How many items to sample? 5
Sample size must be between 1 and 3
```

**Empty input example:**

```text
Enter items separated by commas:
No items entered.
```

**Invalid number example:**

```text
How many items to sample? abc
Please enter a valid number.
```

**Functions used:**

* `random.randint()` generates random integers.
* `random.choice()` selects a random character.
* `random.sample()` selects unique items from the supplied population.

### 11.6 Return to Main Menu

**Input:**

```text
Enter your choice: 6
```

The program returns to the main menu.

---

## 12. UUID Generation

This section uses the `uuid` module.

### Purpose

UUID stands for Universally Unique Identifier. The program generates an identifier using the `uuid.uuid4()` function.

### Input

```text
Enter your choice: 4
```

### Example Output

```text
--- Generate Unique Identifiers (UUID) ---
Generated UUID: 8f7b9c2e-1234-4a56-89ab-1234567890ab
```

The displayed UUID is illustrative. The program generates a new UUID when the option is selected.

### Function Used

`uuid.uuid4()` generates a UUID using random or pseudorandom data.

UUIDs are useful when demonstrating unique identifiers for records, objects, and other application resources.

---

## 13. File Operations

This section demonstrates basic file handling using Python's `open()` function.

### File Operations Menu

```text
--- File Operations (Custom Module) ---
1. Create a new file
2. Write to a file
3. Read from a file
4. Append to a file
5. Back to Main Menu
Enter your choice:
```

### 13.1 Create a New File

**Purpose:** Creates a new file if the filename does not already exist.

**Input:**

```text
Enter your choice: 1
Enter file name: notes.txt
```

**Output:**

```text
File created successfully.
```

If the file already exists:

```text
File already exists.
```

**Function:** `create_file(filename)`

**File mode:** `x`

The `x` mode creates a new file and raises `FileExistsError` if the file already exists.

### 13.2 Write Data to a File

**Purpose:** Writes user-provided text into a file.

**Input:**

```text
Enter your choice: 2
Enter file name: notes.txt
Enter data to write: Hello Python
```

**Output:**

```text
Data written successfully.
```

The text is written into the file.

**File mode:** `w`

The `w` mode overwrites existing content when the file already exists. If the file does not exist, Python normally creates it.

**Function:** `write_file(filename, data)`

### 13.3 Read Data from a File

**Purpose:** Reads and displays the contents of an existing file.

**Input:**

```text
Enter your choice: 3
Enter file name: notes.txt
```

**Output:**

```text
Hello Python
```

**File mode:** `r`

**Function:** `read_file(filename)`

If the file does not exist:

```text
File not found.
```

### 13.4 Append Data to a File

**Purpose:** Adds new text to the end of a file without removing its existing content.

**Input:**

```text
Enter your choice: 4
Enter file name: notes.txt
Enter data to append: Welcome to Python
```

**Output:**

```text
Data appended successfully.
```

If the original content was `Hello Python`, the file will contain:

```text
Hello PythonWelcome to Python
```

The two strings appear together because the current program does not automatically add a newline when writing or appending data.

**File mode:** `a`

**Function:** `append_file(filename, data)`

The `a` mode appends data to the end of the file and creates the file if it does not exist.

### 13.5 Return to Main Menu

**Input:**

```text
Enter your choice: 5
```

The program returns to the main menu.

### File Modes Summary

| Mode | Description                                       |
| ---- | ------------------------------------------------- |
| `x`  | Creates a new file and fails if it already exists |
| `w`  | Writes data, overwriting existing content         |
| `r`  | Reads existing file content                       |
| `a`  | Appends data to the end of a file                 |

---

## 14. Explore Module Attributes

This section demonstrates dynamic imports and module inspection.

### Purpose

The user enters the name of a Python module. The program imports the module dynamically and displays its available names using `dir()`.

### Input

```text
Enter your choice: 6
Enter module name to explore: math
```

### Example Output

```text
--- Explore Module Attributes (dir()) ---
Available Attributes in math:
['__doc__', '__loader__', '__name__', '__package__', '__spec__', 'acos', 'asin', 'atan', 'ceil', 'comb', 'cos', 'degrees', 'e', 'exp', 'factorial', 'floor', 'fmod', 'frexp', 'gcd', 'hypot', 'inf', 'isclose', 'isfinite', 'isinf', 'isnan', 'isqrt', 'lcm', 'log', 'pi', 'pow', 'radians', 'sin', 'sqrt', 'tan', 'trunc']
```

The list above is illustrative and abbreviated. The actual list depends on the module and Python version.

### Example with the Random Module

**Input:**

```text
Enter module name to explore: random
```

**Example output:**

```text
Available Attributes in random:
['Random', '__all__', '__builtins__', '__cached__', '__doc__', '__file__', '__loader__', '__name__', '__package__', '__spec__', 'choice', 'choices', 'randint', 'random', 'sample', 'shuffle', 'uniform']
```

This is an illustrative selection of attributes, not a guaranteed complete list.

### Invalid Module Example

**Input:**

```text
Enter module name to explore: abcxyz
```

**Output:**

```text
Module not found.
```

### Functions Used

**`importlib.import_module(module_name)`**

Imports a module based on the name entered by the user.

**`dir(module)`**

Returns a list of names defined by or available from the module.

---

## 15. Functions Used in the Project

The following functions are defined in the supplied Python program.

### Date and Time Function

**`datetime_menu()`**

Displays the date and time submenu and runs the selected operation.

### Mathematical Functions

**`factorial(num)`**

Returns the factorial of a number using `math.factorial()`.

**`compound_interest(principal, rate, years)`**

Calculates and returns compound interest using the principal amount, interest rate, and time period.

**`trigonometry(angle)`**

Converts an angle into radians and returns a dictionary containing the sine, cosine, and tangent values.

**`circle_area(radius)`**

Returns the area of a circle.

**`rectangle_area(length, width)`**

Returns the area of a rectangle.

**`triangle_area(base, height)`**

Returns the area of a triangle.

**`mathmatical_menu()`**

Displays the mathematical menu and processes the selected operation. The spelling `mathmatical_menu` matches the supplied code.

### Random Function

**`random_menu()`**

Displays the random data generation menu and handles random numbers, lists, passwords, OTPs, and sampling.

### UUID Function

**`uuid_menu()`**

Generates and displays a UUID.

### File Functions

**`create_file(filename)`**

Attempts to create a new file and returns a success or already-exists message.

**`write_file(filename, data)`**

Writes data into a file and returns a status message.

**`read_file(filename)`**

Reads file contents and returns the text or a missing-file message.

**`append_file(filename, data)`**

Appends data to a file and returns a status message.

**`file_menu()`**

Displays the file operations menu and calls the corresponding file functions.

### Module Exploration Function

**`explore_module()`**

Imports a module dynamically and displays its attributes using `dir()`.

### Main Function

**`main()`**

Displays the main menu, calls the relevant menu functions, and exits when the user selects option 7.

### Program Entry Point

```python
if __name__ == "__main__":
    main()
```

This condition calls `main()` when the file is executed directly as a Python program.

---

## 16. Python Concepts Practiced

This project demonstrates the following concepts.

### 16.1 Variables and Data Types

The program uses variables to store user choices, dates, numbers, strings, lists, dictionaries, and file contents.

### 16.2 User Input and Output

`input()` accepts user input, while `print()` displays menus, results, and error messages.

### 16.3 Functions

User-defined functions divide the program into smaller, reusable sections.

### 16.4 Conditional Statements

The program uses `if`, `elif`, and `else` to decide which operation should run.

### 16.5 Loops

`while` loops keep menus running until the user chooses to return or exit.

`for` loops perform repeated operations, such as countdown updates and random list generation.

### 16.6 Lists and List Comprehensions

Lists store random numbers and user-provided items.

List comprehensions create random lists and filter empty values during random sampling.

### 16.7 Dictionaries

The `trigonometry()` function returns its results in a dictionary with the keys `sin`, `cos`, and `tan`.

### 16.8 Modules and Packages

The program imports standard library modules and a custom package.

### 16.9 Dynamic Imports

`importlib.import_module()` loads a module using a name provided by the user.

### 16.10 File Handling

The program creates, writes, reads, and appends file content.

### 16.11 Exception Handling

`try` and `except` blocks manage common errors such as invalid inputs and missing files.

### 16.12 String Formatting

F-strings format results such as trigonometric values, compound interest, and countdown messages.

### 16.13 Date and Time Formatting

`strptime()` parses dates, while `strftime()` formats them for display.

### 16.14 The `break` and `continue` Statements

`break` exits a loop, while `continue` skips the remaining statements in the current iteration and starts the next iteration.

### 16.15 The Main Guard

The `if __name__ == "__main__":` condition ensures that the main function is called when the file is executed directly.

---

## 17. Error Handling

The program uses exception handling to manage several common errors.

| Situation                                       | Expected program message or behavior            |
| ----------------------------------------------- | ----------------------------------------------- |
| Invalid date format                             | Displays an invalid date format message         |
| Invalid numeric input for dates or calculations | Displays an appropriate validation message      |
| Negative countdown                              | Displays a positive-number message              |
| Invalid menu choice                             | Displays `Invalid choice!` or `Invalid choice.` |
| File already exists in `x` mode                 | Displays `File already exists.`                 |
| File does not exist during reading              | Displays `File not found.`                      |
| Module cannot be imported                       | Displays `Module not found.`                    |
| Empty random sampling input                     | Displays `No items entered.`                    |
| Invalid random sample size                      | Displays the allowed sample-size range          |

Some exceptions are handled with a general `except Exception as e` block in the file-writing and appending functions. This allows the program to return an error message if an operation fails.

**Important limitation:** Not every possible error is handled. For example, the current program does not reject negative circle radii or negative rectangle dimensions. Some invalid mathematical inputs may also produce results that need additional validation.

---

## 18. Learning Outcomes

By developing this project, I practiced combining multiple Python concepts into one menu-driven application.

I learned how to:

* Import and use standard library modules.
* Create reusable user-defined functions.
* Organize code into different functional sections.
* Work with dates and time.
* Perform mathematical calculations.
* Generate random values and sample data.
* Generate UUID identifiers.
* Create and manipulate files.
* Handle common exceptions.
* Dynamically import modules and inspect their attributes.
* Display results and error messages through a console interface.

This project strengthened my understanding of Python fundamentals and provided practical programming experience.

---

## 19. Future Improvements

The project can be improved in the following ways:

* Connect the custom module functions to the menu operations.
* Add more mathematical operations.
* Improve input validation for all calculations.
* Validate negative values where appropriate.
* Add better date and time input options.
* Use the `secrets` module for secure password and OTP generation.
* Add a graphical user interface using Tkinter.
* Add automated tests for individual functions.
* Improve file-writing and appending formats.
* Add logging to record program errors.
* Separate the project into cleaner modules.
* Add more useful utility operations.

---

## 20. Author

**Sneha Padsala**

Python Learner | Practicing Python Modules, Functions, File Handling, and Programming Fundamentals.

This project is part of my Python programming practice and learning journey.

---

## 21. Conclusion

The Multi-Utility Toolkit is a Python console application that combines date and time utilities, mathematical calculations, random data generation, UUID generation, file handling, and module exploration.

It demonstrates how Python's standard library, user-defined functions, conditional statements, loops, exception handling, and file operations can work together in a single menu-driven application.

The project provides practical experience with Python programming fundamentals and serves as a foundation for developing more advanced applications in the future.
