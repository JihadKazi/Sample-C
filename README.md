# Grade Calculator in C

A simple C program that calculates a student's grade based on their marks.

## Features

* Takes user input for marks.
* Displays grade based on the following scale:

  * **A+** : 80–100
  * **A**  : 60–79
  * **B**  : 40–59
  * **Fail** : below 40

## Usage

1. Compile the program using a C compiler:

   ```bash
   gcc grade_calculator.c -o grade_calculator
   ```
2. Run the executable:

   ```bash
   ./grade_calculator
   ```
3. Enter your marks when prompted, and see your grade.

## Example

```
Enter your marks: 75
Your grade is A
```

## Notes

* Input should be an integer between 0 and 100.
* Program prints a humorous message for failing marks.
