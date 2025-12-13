# student-report-card-system.

A **comprehensive Student Report Card System** built in Python to efficiently manage student academic records. This system allows adding, updating, and viewing student marks, calculating grades, analyzing pass/fail status, detecting toppers, and finding the highest scores per subject.

---

## Table of Contents
- [About](#about)  
- [Features](#features)  
- [Technologies](#technologies)  
- [Example Output](#example-output)  
- [Contributing](#contributing)  
   

---

## About
The Student Report Card System is a command-line interface (CLI) application designed for educational institutions or personal projects. It simplifies storing student records, calculating grades, and generating report card summaries, making student performance analysis easy and accurate.

---

## Features
- ✅ Add new student records with subject-wise marks  
- ✅ View detailed student report cards with grades  
- ✅ Update student marks  
- ✅ Automatic grade calculation (A+, A, B+, B, C, F)  
- ✅ Pass/Fail analysis for each student  
- ✅ Detect the topper based on average marks  
- ✅ Display the highest score per subject  
- ✅ List all students for quick reference  
- ✅ Data stored persistently using JSON  

---

## Technologies
- **Programming Language:** Python 3.x  
- **Data Storage:** JSON file (`students.json`)  
- **Interface:** Command-Line Interface (CLI)  

---

## output
=== Student Report Card System ===
1. Add Student
2. View Student Report Card
3. Update Student Marks
4. List All Students
5. Show Topper
6. Show Highest Score per Subject
7. Exit
Enter your choice:

##Adding a Student:

Enter Student ID: 101

Enter Student Name: Alice

Enter marks for Math: 95

Enter marks for Science: 88

Enter marks for English: 92

Student Alice added successfully!

##VIEWING REPORT CARD

--- Report Card: Alice ---
Math: 95  Grade: A+ 

Science: 88  Grade: A

English: 92  Grade: A+
Total Marks: 275

Average Marks: 91.67

Overall Grade: A+

Result: Pass

##UPDATING STUDENT MARKS

Enter Student ID: 101

Enter new marks for Math (current: 95): 98

Enter new marks for Science (current: 88): 90

Enter new marks for English (current: 92): 94

Marks updated successfully!


##TOPPER DETECTION

Topper: Alice with Average Marks: 91.67


##HIGHEST SCORE PER SUBJECT

--- Highest Scores ---

Math: 95 by Alice

Science: 88 by Alice

English: 92 by Alice


