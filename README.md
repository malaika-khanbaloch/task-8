Binary Search Tree (BST) for Managing Student Information
Overview
This C++ program demonstrates how to use a Binary Search Tree (BST) to manage and store student information, including their marks and gender. It organizes students into two separate BSTs: one for male students and another for female students. The program offers functionality to insert new student data, display the BSTs through in-order traversal, and exit the program.

Key Features
Binary Search Tree (BST) data structure implementation.
Separate BSTs for male and female student data.
Insertion of student records into the appropriate BST based on gender.
In-order traversal to display student information in sorted order.
Simple and interactive menu for user interaction.
Classes
TreeNode: Defines a node in the BST that holds student marks, gender, and pointers to the left and right child nodes.
BST: Defines the Binary Search Tree itself, with methods for inserting data and performing in-order traversal to display the student records.
Functions
insert: Adds a new student node to the appropriate position in the BST.
inOrder: Performs an in-order traversal of the BST, printing the student data in sorted order.
main: The main driver function, which provides a menu-based interface for the user to interact with the program.
How to Use
Compile the code using a C++ compiler (e.g., g++).
Execute the compiled program.
Choose from the following menu options:
1: Initialize the BSTs (insert student data).
2: Display the BST for male students.
3: Display the BST for female students.
0: Exit the program.
