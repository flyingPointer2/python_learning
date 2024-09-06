# 关于

> 关于作者 flyingPointer2 的介绍

Let pointers fly!

But before the pointers flying, let's make them point to something.

Firstly, point to some variables (including `int`, `double` or `char`, etc.) after they are defined.

```c++
int number_of_students = 99;
int * pn = &number_of_students;

std::cout << "The value of variable `number_of_students` is: " << (*pn) 
    << " or " << number_of_students << std::endl;
std::cout << "The address of variable `number_of_students` is: " << (pn) 
    << " or " << &number_of_students << std::endl;
```

Secondly, point to some arrays (including arrays of `int`, `double` or `char`, etc.) after they are initialized.

```c++
char name[] = "Sherlock Holmes";
char * pc = name;   // or `pc = &name[0]`

std::cout << "The second letter of the name is " << 
    name[1] << " or " <<
    pc[1] << " or " <<
    *(pc+1) << std::endl;
```

Thirdly, point to some dynamically allocated memories ...

......
