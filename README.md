# Age_calculator.C
A simple C program that calculates  a user's exact age based on their  birth year .

#include <stdio.h>

int main() {
    int currentyear=2026, birthyear=2008, myage;
    myage = currentyear - birthyear;
    printf("myage=%d\n", myage);
    
    return 0;
}
