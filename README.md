#STUDENT RECORD MANAGEMENT SYSTEM


This is a simple C++ program that implements a Student Management System using a linked list. The system allows you to perform the following operations:
- Insert a new student record
- Search for a student record by roll number
- Count the number of student records
- Update an existing student record
- Delete a student record
- Show all student records


## Getting Started

To run this program, you need to have a C++ compiler installed on your system. You can use any compiler of your choice, such as GCC or Clang.

### Compilation

To compile the program, navigate to the directory containing the source code and run the following command:


g++ -o student_management main.cpp


This will create an executable file named `student_management`.

### Running the Program

To run the compiled program, use the following command:


./student_management


## Usage

After running the program, you will be presented with a menu that allows you to choose the operation you want to perform. The options are:

1. Insert Record
2. Search Record
3. Count Nodes
4. Update Record
5. Delete Record
6. Show All Records
0. Exit

You can enter the corresponding number to perform the desired operation.

## Functions

### `void insert()`

This function inserts a new student record into the linked list. It prompts the user for the student's roll number, name, marks, CGPA, number of courses taken, and the names of the courses. It then calculates the percentage based on the marks and inserts the new node at the end of the list.

### `void search()`

This function searches for a student record by roll number. If a matching record is found, it displays the student's details. If no matching record is found, it displays a message indicating that the record was not found.

### `void count()`

This function counts and displays the number of student records in the linked list.

### `void update()`

This function updates an existing student record. It prompts the user for the roll number of the student to be updated. If a matching record is found, it prompts the user for the new details and updates the record. If no matching record is found, it displays a message indicating that the record was not found.

### `void deletefunc()`

This function deletes a student record by roll number. If a matching record is found, it deletes the node from the linked list. If no matching record is found, it displays a message indicating that the record was not found.

### `void show()`

This function displays all student records in the linked list.
