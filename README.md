# Assignment_BTech2026_-2201921530037-


## Problem Statement
The task is to create a class named `Student` that encapsulates the details of a student, including their age, first name, last name, and standard. The class should provide methods to set and get these attributes, as well as a method to return a string representation of the student.

## Coding Platform Used
- C++
- HACKERANK

## Approach and Solution Explanation
1. **Class Definition**: 
   - A class named `Student` is defined with private attributes:
     - `ages`: an integer representing the student's age.
     - `standards`: an integer representing the student's standard (grade).
     - `first`: a string representing the student's first name.
     - `last`: a string representing the student's last name.

2. **Setter Methods**: 
   - The class provides public methods to set the values of the private attributes:
     - `set_age(int age)`: Sets the age of the student.
     - `set_standard(int standard)`: Sets the standard of the student.
     - `set_first_name(string first_name)`: Sets the first name of the student.
     - `set_last_name(string last_name)`: Sets the last name of the student.

3. **Getter Methods**: 
   - The class provides public methods to retrieve the values of the private attributes:
     - `get_age()`: Returns the age of the student.
     - `get_standard()`: Returns the standard of the student.
     - `get_first_name()`: Returns the first name of the student.
     - `get_last_name()`: Returns the last name of the student.

4. **String Representation**: 
   - A method `to_string()` is implemented to return a formatted string containing the student's details in the format: `age,first_name,last_name,standard`.

5. **Main Function**: 
   - In the `main()` function, user input is taken for age, first name, last name, and standard.
   - An object of the `Student` class is created, and the input values are set using the setter methods.
   - Finally, the details are printed using the getter methods and the `to_string()` method.

                                                                                                                                                                                                                                                                                                                                   
                                                         *****ASSIGNMENT  2******                                                                                   ## Problem statement
     
 The problem requires implementing a program that reads the scores of multiple students in five subjects, calculates their total scores, and determines how many students have a higher total score than the first student (Kristen).

**Coding Platform Used**

The solution is implemented in C++ and is designed to run in any standard C++ environmeNT:

HackerRank



***Approach and Solution Explanation***

Class Implementation:

A Student class is created with a private vector<int> scores to store the scores.

The input() function takes input for five subjects and stores them in the scores vector.

The calculateTotalScore() function iterates through the scores vector to compute and return the total score.

Main Function Execution:

Reads the number of students.

Creates an array of Student objects dynamically.

Calls the input() function for each student to take their scores.

Calculates the total score of the first student (Kristen).

Iterates through the rest of the students to check how many have a higher total score than Kristen.

Prints the count of students who scored higher than Kristen.

                       
