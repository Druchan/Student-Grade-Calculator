
# Student Grade Calculator

This Java program calculates the total marks, percentage, average, and grade of a student based on their marks in five subjects. The program prompts the user to input their name, roll number, and marks for each subject, then computes and displays the results.

## How to Use

1. The program will prompt you to enter the following details:
    - Name
    - Roll Number
    - Marks for Tamil
    - Marks for English
    - Marks for Maths
    - Marks for Science
    - Marks for Social
2. The program will calculate the total marks, percentage, average marks, and grade based on the entered marks.
3. The calculated results will be displayed.

## Grading Criteria

- **A**: Average marks >= 90
- **B**: Average marks >= 80 and < 90
- **C**: Average marks >= 65 and < 80
- **D**: Average marks >= 45 and < 65
- **E**: Average marks >= 35 and < 45
- **F**: Average marks < 35

## Example

```
Enter your Name :
Dru
Enter your Roll Number :
41
Enter your Tamil Mark :
85
Enter your English Mark :
78
Enter your Maths Mark :
92
Enter your Science Mark :
88
Enter your Social Mark :
81

Roll Number : 41
Name : Dru
Tamil Mark : 85
English Mark : 78
Maths Mark : 92
Science Mark : 88
Social Mark : 81
Your Total Mark is : 424
Your Percentage is : 84.8
Your Average is : 84
Your Grade is : B
```

## Code Overview

The main components of the code are as follows:

- **User Input:** Uses `Scanner` class to read user details and marks from the console.
- **Calculations:**
  - **Total Marks:** Sum of marks in all five subjects.
  - **Percentage:** Calculated as `(total marks / 500) * 100`.
  - **Average Marks:** Calculated as `total marks / 5`.
  - **Grade:** Determined based on the average marks.
- **Output:** Displays the entered details, total marks, percentage, average marks, and grade.

## Usage

To run the program, compile and execute the `StudentGradeCalculator` class.

### Compilation

```bash
javac StudentGradeCalculator.java
```

### Execution

```bash
java StudentGradeCalculator
```

## Author

- Chandru S

## License

This project is licensed under the MIT License.

---
