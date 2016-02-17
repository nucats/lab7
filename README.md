# EECS 230 Lab 7

In this lab, you will review and work on solidifying your intuition with pointers.

1. Review Memory, Free Store, References, and Pointers
2. What are the differences between pointers and references?

## Exercises

1. Write a function `void pointer_fun(int a, int b)`, that creates two integer pointers named ptrA and ptrB that point to ints a and b, respectively. Print to terminal the values of the ints at the pointers. Then, print to terminal the pointer locations. How far away, in bytes, is location of ptrA versus location of ptrB?

2. Write a function `short greater_val(short * ptrA, short * ptrB)` that takes two pointers to shorts, and returns the value of whichever short is greater.

3. Write a function `void pointer_arithmetic_chars()` that takes an array of characters (`char[]`)  and iterates over the characters via a pointer to print the sentence.

4. Purposely put a bug somewhere in the functions above, and use the debugger and well-placed breakpoints to find the bug.

5. Allocate a new int with space from the heap store, in a helper function; use `int * ip = new int(4)`. Print out that pointer's value in `main()`.

6. Work through creating a vector of all the students in your section.

 Use the following class definition:
```
class Student
{
    public:
        Student();
        Student(string f_name, string l_name, int g_year);
        
    private:
        string first_name_;
        string last_name_;
        int grad_year_;
}
```
Create and test the following functions: `void add_student()` and `void remove_student()`.