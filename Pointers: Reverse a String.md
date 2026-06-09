# Pointers: Reverse a String Using Pointers in C

## 🎯 Aim

To write a C program that prints a string in reverse using a pointer.

## 🧠 Algorithm

1. **Input**: Read a string from the user.
2. **Reverse String**:
   - Use a pointer to traverse the string to find its length.
   - Then, move the pointer to the last character of the string.
   - Print characters in reverse by decrementing the pointer.
3. **Output**: Display the reversed string.

## Program
```
#include <stdio.h>
int main() {
    char str[100];
    char *ptr;
    printf("Enter a string: ");
    scanf("%s", str);
    ptr = str;
    while(*ptr != '\0') {
        ptr++;
    }
    ptr--;
    printf("Reversed string: ");
    while(ptr >= str) {
        printf("%c", *ptr);
        ptr--;
    }

    return 0;
}
```

## Output
<img width="909" height="252" alt="image" src="https://github.com/user-attachments/assets/79dea7a4-a2f6-47d9-84d3-ee4f8f303782" />

## Result
C program to prints a string in reverse using a pointer is written.
