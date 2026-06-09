# # Pointers: Division of Two Numbers Using Pointers in C

## 🎯 Aim

To write a C program that performs the division of two numbers using pointers.

## 🧠 Algorithm

1. **Declare** integer variables `a`, `b`, and `sub`, and pointers `c`, `d`.
2. **Read** values for `a` and `b` from the user.
3. **Assign** the addresses of `a` and `b` to the pointers `c` and `d` respectively.
4. **Calculate** the quotient by dereferencing the pointers:
   ```c
   sub = *c / *d;
5. Print the result (quotient) stored in sub.

## Program
```
#include <stdio.h>
int main() {
    int a, b, sub;
    int *c, *d;
    printf("Enter two integers:\n");
    scanf("%d %d", &a, &b);
    c = &a;
    d = &b;
    if(*d == 0) {
        printf("Division by zero is not allowed.\n");
    } else {
        sub = (*c) / (*d);
        printf("Quotient = %d\n", sub);
    }

    return 0;
}
```

## Output
<img width="897" height="327" alt="image" src="https://github.com/user-attachments/assets/b2b6024e-2be3-42fd-a23b-c0c15b2947cd" />

## Result
C program to performs the division of two numbers using pointer is written.
