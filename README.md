 Student Performance Analytics System:

A Python-based project that analyzes student marks, calculates totals and averages, assigns grades, determines pass/fail results, and generates a student performance report in CSV format.

 Features:
 Creates a dataset of 15 students with marks in 5 subjects and attendance.
 Saves student data to `students.csv`.
 Calculates each student's Total and Average.
 Assigns grades based on average marks.
 Determines Pass/Fail results.
 Displays class-level statistics.
 Saves the final report to `student_performance.csv`.

 Project Structure:
pythonfolder/
├── main.py
├── students.csv
├── student_performance.csv
└── README.md

 Requirements:
 Python 3.8+
 Pandas
 NumPy

Install dependencies:
pip install pandas numpy

Usage:
Run the program from the project folder:
python main.py

The program generates the student dataset, displays the performance report, and saves the results to CSV files.

 Dataset:

| Column | Description |
|---|---|
| Student_ID | Unique student ID |
| Name | Student name |
| Python | Marks out of 100 |
| SQL | Marks out of 100 |
| HTML | Marks out of 100 |
| CSS | Marks out of 100 |
| JavaScript | Marks out of 100 |
| Attendance | Attendance percentage |

 Grading Rules:

| Average Marks | Grade |
|---|---|
| 90 and above | A+ |
| 80–89.99 | A |
| 70–79.99 | B |
| 60–69.99 | C |
| 50–59.99 | D |
| 40–49.99 | E |
| Below 40 | F |

Pass/Fail Rule: A student passes if they score at least 35 marks in every subject. If they score below 35 in any subject, the result is Fail.

Class Analysis
  The program displays:
Class average
Highest student average
Lowest student average
Number of students passed
Number of students failed

Technologies Used:
Python
Pandas
NumPy
CSV file handling

Possible Improvements
 Add charts for visualizing student performance.
 Include attendance in the pass/fail calculation.
 Generate subject-wise performance analysis.
 Add a student search feature.

License
This project is created for learning and educational purposes.
