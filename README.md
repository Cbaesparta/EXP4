# EXP4
## AIM:
To study and implement C++ Bitwise Operators


# THEORY BITWISE OPERATORS
Explanation of Bitwise Operators
### Bitwise AND (&):

Operation: Performs a logical AND on each bit of the operands.
Example: f & v
### Bitwise OR (|):

Operation: Performs a logical OR on each bit of the operands.
Example: f | v
### Bitwise XOR (^):

Operation: Performs a logical XOR on each bit of the operands, yielding 1 for differing bits.
Example: f ^ v
### Bitwise NOT (~):

Operation: Inverts all bits of the operand.
Example: ~f, ~v
### Bitwise Left Shift (<<) ):

Operation: Shifts bits of the left operand to the left by the number of positions specified by the right operand.
Example: f << 2
### Bitwise Right Shift (>>) :

Operation: Shifts bits of the left operand to the right by the number of positions specified by the right operand.
Example: f >> 2
```
//Sai Sankar Jena
//23070123112
//EnTC B2
//Exp-4 bitwise
#include <iostream>
using namespace std;
int main()
{// Bitwise operators:
    int f, v;
    cout << "\nEnter the first number for bitwise operation: ";
    cin >> f;
    cout << "Enter the second number for bitwise operation: ";
    cin >> v;
    
    cout << "f & v = " << (f & v) << endl;
    cout << "f | v = " << (f | v) << endl;
    cout << "f ^ v = " << (f ^ v) << endl;
    cout << "~(" << f << ") = " << (~f) << endl;
    cout << "~(" << v << ") = " << (~v) << endl;
    return 0;
}
```
### OUTPUT:
![Screenshot 2024-08-02 121317](https://github.com/user-attachments/assets/b9f82240-c5e1-4328-8b4e-5833b6dfca88)



## Conclusion

- **Bitwise operators** in C++ allow for efficient manipulation and analysis of individual bits within integers.
- They are crucial for **low-level data operations** and **performance optimization**.
- The demonstrated operators—**AND (`&`)**, **OR (`|`)**, **XOR (`^`)**, and **NOT (`~`)**—enable powerful bitwise computations.
- Mastery of these operators can enhance the **efficiency of algorithms** and **system-level programming**.
