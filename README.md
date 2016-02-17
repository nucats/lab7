# EECS 230 Lab 7

In this lab, you will review and work on solidifying your intuition with pointers.

1. Review Memory, Free Store, References, and Pointers
2. What are the differences between pointers and references?

## Exercises

1. Write a function `void pointer_fun(int a, int b)`, that creates two integer pointers named ptrA and ptrB that point to ints a and b, respectively. Print to terminal the values of the pointers. Then, print to terminal the value of the ints at the pointer locations.

2. Write a function `long * find_max_long_ptr(vector<long> & v)` that finds the max of an integral data set, and returns a pointer to that location.

3. Write a function `short greater_val(short * ptrA, short * ptrB)` that takes two pointers to shorts, and returns the value of whichever short is greater.

4. Write a function `void pointer_arithmetic(string & s)` that takes a string, for instance "hello", and prints on one line the `char` at string index 0, and a pointer location to that `char`.  Update the pointer to pointer +2. Then, print the `char` at that pointer location and the pointer location.

## Additional Practice

5. Work through creating a vector of all the students in your section.

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
Store pointers to the Students in a global variable `vector<Student *>` enrollees. Create and test the following functions: `void add_student()`, `void remove_student()` , and void `change_grad_year(Student *, int g_yr)`.