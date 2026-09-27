# Task 8 - Simple Data Filtering

## AI & ML Internship -Veda Technology- Day 8

### Objective
The objective of this task is to understand how data can be filtered using conditions in Python. 
A collection of student records was created and different conditions were used to find specific students.

### Tools Used
- Python
- Jupyter Notebook

### Dataset
The dataset contains student information such as:
- Name
- Age
- Department
- Marks

### What I Did

In this task, I:

1. Created a list of student records using dictionaries.
2. Filtered students who scored 80 or above.
3. Filtered students based on their age.
4. Filtered students belonging to the IT department.
5. Used multiple conditions to find IT students who scored 80 or above.
6. Displayed the filtered results in a simple tabular format.

### Concepts Used
- Lists
- Dictionaries
- For loops
- If conditions
- Comparison operators
- Logical `and` operator
- Data filtering

### Example Filtering Condition

```python
if student["department"] == "IT" and student["marks"] >= 80:
    filtered_students.append(student)
