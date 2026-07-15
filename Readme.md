# Interactive Personal Data Collector

## Project Description

The Interactive Personal Data Collector is a simple Python program that collects personal information from the user and displays it in a formatted way. It also calculates the user's approximate birth year based on their age.

This project is useful for beginners who are learning:

- User Input
- Variables
- Data Types
- Type Conversion
- f-Strings
- Python `datetime` Module
- `type()` Function
- `id()` Function

---

## Features

- Collects the user's name.
- Collects the user's age.
- Collects the user's height.
- Collects the user's favorite number.
- Displays the entered information.
- Shows the data type of each input.
- Displays the memory address of each variable using `id()`.
- Calculates the approximate birth year.
- Displays a thank you message before exiting.

---

## Technologies Used

- Python 3.x
- datetime Module

---

## Project Structure

```
Interactive-Personal-Data-Collector/
│
├── personal_data_collector.py
└── README.md
```

---

## How to Run

1. Install Python 3.x on your computer.
2. Save the program as:

```
personal_data_collector.py
```

3. Open Terminal or Command Prompt.
4. Navigate to the project folder.
5. Run the following command:

```bash
python personal_data_collector.py
```

---

## Sample Output

```
Welcome to the Interactive Personal Data Collector!

Please enter your name: Meet
Please enter your age: 20
Please enter your height: 5.8
Please enter your favorite number: 7

Thank you! Here is the information we collected:

Name: Meet (type: <class 'str'> Memory Address: 140632...)
Age: 20 (type: <class 'int'> Memory Address: 9793696)
Height: 5.8 (type: <class 'float'> Memory Address: 140632...)
Favorite Number: 7 (type: <class 'int'> Memory Address: 9793280)

Your birth year is approximately: 2006 based on your age of 20

Thank you for using the Personal Data Collector. Goodbye!
```

---

## Concepts Used

- Variables
- User Input
- Data Types
- Type Casting
- `input()`
- `print()`
- `int()`
- `float()`
- `type()`
- `id()`
- f-Strings
- `datetime` Module

---

## Note

- The calculated birth year is approximate because it is based only on the current year and the user's age.
- The memory address displayed by `id()` may be different each time the program is executed.

---

## Author

Meet Prajapati

Python Beginner Project