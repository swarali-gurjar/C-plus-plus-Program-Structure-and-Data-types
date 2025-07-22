**Description**

This simple C++ console program demonstrates the use of basic data types by allowing the user to input values of different types. It then gives the output of the entered values along with the memory size (in bytes) occupied by each variable.
# C++ Data Types Overview
## Data Types Details

| Type                | Typical Width | Typical Range / Description                              |
|---------------------|---------------|----------------------------------------------------------|
| char                | 1 byte        | -127 to 127 or 0 to 255                                  |
| unsigned char       | 1 byte        | 0 to 255                                                |
| signed char         | 1 byte        | -127 to 127                                            |
| int                 | 4 bytes       | -2,147,483,648 to 2,147,483,647                         |
| unsigned int        | 4 bytes       | 0 to 4,294,967,295                                     |
| signed int          | 4 bytes       | -2,147,483,648 to 2,147,483,647                         |
| short int           | 2 bytes       | -32,768 to 32,767                                       |
| long int            | 8 bytes       | -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 |
| signed long int     | 8 bytes       | same as long int                                        |
| unsigned long int   | 8 bytes       | 0 to 18,446,744,073,709,551,615                         |
| long long int       | 8 bytes       | -(2^63) to (2^63)-1                                     |
| unsigned long long int | 8 bytes     | 0 to 18,446,744,073,709,551,615                         |
| float               | 4 bytes       | ±1.17549e-38 to ±3.40282e+38 (IEEE 754)                  |
| double              | 8 bytes       |±2.22507e-308 to ±1.79769e+308 (IEEE 754)                 |
| long double         | 12 bytes      |Usually wider than double, e.g., ±3.3621e-4932 to ±1.18973e+4932 (on some systems)|
| wchar_t             | 2 or 4 bytes  | 1 wide character                                        |
---

**Conclusion**

Choosing the appropriate storage class is essential for effective memory management, controlling the lifespan and visibility of variables, and ensuring the program runs as intended. Whether it's improving performance with register, preserving variable values using static, or enabling cross-file data access with extern, each storage class plays a unique and important role in writing efficient and maintainable C++ code.

