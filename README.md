# EECS 230 Lab 7

In this lab, you will review and work on solidifying your intuition with pointers.

1. Review Memory, Free Store, References, and Pointers
2. What are the differences between pointers and references?
3. Work through creating a vector of all the students in your section. Use the following class definition:
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
Create functions `add_student()` and `remove_student()` to complete the program.