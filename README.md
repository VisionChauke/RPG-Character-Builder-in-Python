This project is a Python application that allows users to create and visualize a character for an RPG adventure. The program accepts a character name and three stats—Strength, Intelligence, and Charisma—while validating input according to RPG rules. Name validations ensure it is a string, non-empty, under 10 characters, and contains no spaces. Stat validations ensure all stats are integers, each between 1 and 4, and that their sum equals 7 points. Once the inputs pass validation, the program generates a visually formatted character sheet, displaying the name and each stat as a line of filled (●) and empty (○) dots for easy reading.

Key Features:

Name validation: type, length, emptiness, and spaces

Stat validation: type, range (1–4), and total sum (7 points)

Visual stat representation using dots for easy reference

Clear and informative error messages for invalid inputs

Fully functional and modular, with separate functions for validation and formatting

Example Output:

ren
STR ●●●●○○○○○○
INT ●●○○○○○○○○
CHA ●○○○○○○○○○


This project demonstrates Python fundamentals including functions, conditionals, loops, string formatting, and input validation, while providing an interactive and fun RPG-inspired experience.
