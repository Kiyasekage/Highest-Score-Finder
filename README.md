# Highest Score Finder

A simple Python program that finds the highest score in a list. The program allows users to choose between using a predefined list of scores or entering their own list. It validates user input, iterates through the list using a loop, and determines the highest score without relying on Python's built-in `max()` function. This project is ideal for beginners who want to practice lists, loops, conditional statements, input validation, and basic algorithms.

## Features

* Choose between a predefined score list or a custom score list.
* Accepts multiple user-entered scores.
* Validates that custom scores are within the range of **0–100**.
* Finds the highest score using a loop and comparison.
* Demonstrates list manipulation, loops, and input validation.
* Displays the highest score along with the user's name.

## How to Run

1. Make sure Python 3 is installed.
2. Run the script:

   ```bash
   python highest_score_finder.py
   ```
3. Choose whether to use the predefined list or enter your own scores.
4. If creating your own list, enter the number of scores followed by each score.

## Example

```text
Welcome to finding your highest score from list!
What's your name? John

Would you like to use
1. Our own setup list [90,70,50,40,34]
2. You fill your own score list
Please enter 1 or 2 : 2

How many score do you want to enter : 5
Please input your score in 100 base percentile(1-100) : 88
Please input your score in 100 base percentile(1-100) : 92
Please input your score in 100 base percentile(1-100) : 75
Please input your score in 100 base percentile(1-100) : 90
Please input your score in 100 base percentile(1-100) : 84

Your highest score is 92, John
Thank you for using our program, John
```

## Language

* Python 3
