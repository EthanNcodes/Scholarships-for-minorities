# Scholarships-for-minorities
# Minority Scholarship Finder

## Overview
This project is a Java console program that helps students find scholarships based on their background and GPA. The program asks the user for some basic information and then suggests scholarships they might qualify for.

The goal of this project is to demonstrate the use of Java programming concepts such as loops, arrays, conditionals, and user input.

## How the Program Works
When the program starts, the user is shown a main menu. They can choose to continue or exit the program.

If they continue, the program will ask for:
- Their name
- The School they attended
- The minority group they identify with
- Whether they are in-state or out-of-state
- The school they attend
- Their GPA

After the information is entered, the program displays the user's information and recommends scholarships based on their GPA and category.

## GPA Requirements
The program determines scholarship availability based on GPA:

- **Below 2.50** – No scholarships available
- **2.50 – 3.20** – Four scholarships available
- **Above 3.20** – Eight scholarships available

## Programming Concepts Used
This project demonstrates several core Java concepts:

- User input using the `Scanner` class
- While loops for menu navigation
- If/else statements for decision making
- Arrays for storing user information
- Input validation for GPA values

## How to Run the Program

1. Compile the program:
```
javac Main.java
```

2. Run the program:
```
java Main
```

## Files in This Project

```
Main.java   - The main Java program
README.md   - Documentation for the project
```
