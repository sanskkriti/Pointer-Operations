
C++ provides two pointer operators, which are (a) Address of Operator &amp; and (b) Indirection Operator *.  A pointer is a variable that contains the address of another variable or you can say that a variable that contains the address of another variable is said to "point to" the other variable. 



# **AIM**
Call by Value and Call by Reference using pointer 

## **THEORY**
In the case of **Call by Value**, when we pass the value of the parameter during the calling of the function, it copies them to the function’s actual local argument.
In the case of **Call by Reference**, when we pass the parameter’s location reference/address, it copies and assigns them to the function’s local argument. Thus, both the actual argument and passed parameters refer to one similar location.



### **ALGORITHM**

**Call by Value**

1.Define a function that takes a pointer as a parameter.

2.Inside the function, you can access and modify the data pointed to by ptr. Changes made to *ptr will affect the original data in the calling code.

3.In the main program, declare a variable and initialize it.

**Call by Reference**

1.Define a function that takes a pointer as a parameter.

2.Inside the function, you can access and modify the value at the memory location pointed to by x. Changes made to *x will affect the original variable from the calling code.

3.Call the function from your main program and pass the address (pointer) of the variable you want to modify.

These algorithms demonstrate how to implement call by value and call by reference using pointers in C++. Remember that in the call by value method, a copy of the argument is passed to the function, while in the call by reference method using pointers, the function receives the address of the original variable, allowing it to modify the original variable.

### **OUTPUT**
![Screenshot 2023-10-18 at 9 15 05 PM](https://github.com/sanskkriti/Pointer-Operations/assets/140137289/c7fdd453-480f-48c3-b9c6-2d3015fb15e0)

