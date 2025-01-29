# Assignment_BTech2026_-2201921530037-


## Problem Statement
The task is to create a class named `Student` that encapsulates the details of a student, including their age, first name, last name, and standard. The class should provide methods to set and get these attributes, as well as a method to return a string representation of the student.

## Coding Platform Used
- C++

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

## Code
```cpp
#include <iostream>

using namespace std;

class Student {
    private:
        int ages, standards;
        string first, last;
    public:  
        void set_age(int age) {
            ages = age;     
        }
        void set_standard(int standard) {
            standards = standard;
        }
        void set_first_name(string first_name) {
            first = first_name;
        }
        void set_last_name(string last_name) {
            last = last_name;
        }
    
        int get_age() {
            return ages;     
        }
        int get_standard() {
            return standards;
        }
        string get_first_name() {
            return first;
        }
        string get_last_name() {
            return last;
        }
      
        string to_string() {
            return std::to_string(ages) + "," + first + "," + last + "," + std::to_string(standards);
        }
};

int main() {
    int age, standard;
    string first_name, last_name;
    
    cin >> age >> first_name >> last_name >> standard;
    
    Student st;
    st.set_age(age);
    st.set_standard(standard);
    st.set_first_name(first_name);
    st.set_last_name(last_name);
    
    cout << st.get_age() << "\n";
    cout << st.get_last_name() << ", " << st.get_first_name() << "\n";
    cout << st.get_standard() << "\n";
    cout << "\n";
    cout << st.to_string();
    
    return 0;
}
