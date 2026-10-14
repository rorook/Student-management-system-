Student Grade Management System
A menu-driven C++ console program that stores student marks in an array and lets you add, view, search, sort, delete and analyse them. It was built as a real-world example of an application that depends on arrays.
Features
Add a student (name and mark from 0 to 100)
View all students with letter grades
Search by name (partial match, not case-sensitive)
Sort by mark, highest first
Statistics: number of students, average, highest and lowest mark
Delete a student
Load sample data for a quick demo
How arrays are used
The program is built around one fixed-size array: Student students[100].
Feature
Array technique
Add
Insert at the next free index
View, Statistics
Traverse with a for loop
Search
Linear search
Sort
Selection sort (swapping elements)
Delete
Shift later elements one place to the left
The array is also passed to functions, so each feature is its own small function.
Build and run
Any C++11 (or newer) compiler works, for example g++:
g++ -std=c++17 main.cpp -o grades
./grades
On Windows, run grades.exe instead of ./grades.
Grading scale
A: 80 and above, B: 70-79, C: 60-69, D: 50-59, F: below 50. Edit letterGrade() in main.cpp to match your own scale.
