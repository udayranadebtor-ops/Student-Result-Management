Student Result Management System

A beginner-friendly, menu-driven Python program to manage student results through the console. This system allows you to add new students, input marks for a fixed set of subjects, and view overall or individual results—with grades and pass/fail status automatically calculated.

Features
Add student information: name, roll number, class/section, and marks in all subjects.

Marks entry with validation (numbers only, range 0–100).

Stores marks for Maths, Science, English, Computer, Hindi.

Calculates total, percentage, grade (A+, A, B+, B, C, F), and pass/fail status (Pass for % ≥ 50).

View individual student result by roll number.

View a summary list of all students (showing roll number, name, class, percentage, grade, and status).

Prevents duplicate roll numbers.

Easy-to-understand command-line interface.

How to Run
Make sure you have Python 3 installed.

Save your code as student_result_system.py.

Open a terminal or command prompt and navigate to the folder containing the script.

Run:

text
python student_result_system.py
Use the menu by entering the number corresponding to your desired action (add, view summary, view result, exit).

Example Subjects
Maths

Science

English

Computer

Hindi

Menu Options
Add New Student:
Input roll number, name, class/section, and marks for each subject.

View All Students Summary:
Shows a table of all entered students and their result summaries.

View Individual Student Result:
Enter a roll number to get full marks, total, percentage, grade, and pass/fail.

Exit:
Leave the program.

Code Structure
input_marks(): Takes and validates subject marks.

calculate_result(marks): Computes total, percentage, grade, and status.

add_student(): Adds students safely (no duplicate roll numbers).

view_all_students(): Shows summaries for all students.

view_student_result(): Shows details for a specific student.

main_menu(): Runs the main loop and displays the menu.

Notes
All information is stored in memory for the session.
(Data will be lost if the program is closed.)

Only valid, non-duplicate students are stored.

License
This project is provided for learning purposes.
