# Student Marks Management Application

A simple web application to manage student marks, built with HTML, CSS and JavaScript.
It uses lists, tuples, dictionaries and file processing.

## Features
- Add and delete students (roll no, name, marks of 5 subjects)
- Automatic total, percentage, grade and pass/fail result
- Search by name or roll no, and sort by roll no, name or total
- Class summary: number of students, average, topper, pass/fail count
- File processing: save and load data in `marks.txt` format, and import from a `.txt` file

## Data structures
| Concept | Used for |
|---|---|
| Tuple | Fixed subject names and each student's marks |
| Dictionary | One student record (`roll`, `name`, `marks`) |
| List | Collection of all student records |
| File | `marks.txt`, one student per line |

In JavaScript, a list is an array, a dictionary is an object and a tuple is a frozen array.

## File format
```
roll,name,maths,physics,chemistry,english,computer
101,Aarav,78,85,72,80,91
```

## Grading
- Percentage = total marks / 5
- A+ (90+), A (80+), B (70+), C (60+), D (40+), F (below 40)
- A student passes only if every subject mark is 40 or more

## How to run
Open `index.html` in any browser. No installation needed.

## Author
Your Name, Roll No, College
