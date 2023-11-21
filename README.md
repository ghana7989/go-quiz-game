
# Quiz Game in Go

## Introduction

This Go program is a simple quiz game that reads questions and answers from a CSV file and tests the user within a specified time limit. It was developed as a part of learning Go programming language.

## Features

- **CSV File Input**: The program accepts a CSV file as input, containing questions and answers in the format `question,answer`.
- **Customizable Time Limit**: Users can set their own time limit for the quiz.
- **Interactive Quiz**: The quiz runs in the command line, asking each question one at a time.
- **Score Tally**: At the end of the quiz or when the time limit expires, the program displays the user's score.

## How to Run

1. **Install Go**: Ensure you have Go installed on your machine.
2. **Compile the Program**: Navigate to the directory containing the program and compile it using `go build`.
3. **Prepare CSV File**: Create a CSV file named `problems.csv` (or another name of your choice) in the format `question,answer`. Place this in the same directory as the program.
4. **Execute the Program**: Run the program using `./[program name]`. Optionally, you can specify the CSV file and time limit using flags `-csv` and `-limit`. For example: `./[program name] -csv=yourfile.csv -limit=30`.

## Usage Example

```bash
./quizgame -csv=problems.csv -limit=30
```

## Notes

- This program is ideal for those looking to practice Go language basics, including file I/O, parsing CSV files, using goroutines and channels, and handling command line arguments.
- The CSV file should be formatted correctly to ensure the program runs smoothly.

Developed as an educational project for understanding and practicing Go programming concepts.
