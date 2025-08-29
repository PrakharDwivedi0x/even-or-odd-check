# even-or-odd-check

#include <stdio.h>

int main() {
    int number;
    printf("enter an integer:");
    scanf("%d", &number);
    if( number % 2 == 0 ){
        printf("%d is an evennumber.\n" , number);}
        
        else{
            printf("%d is odd.\n" , number);}
    }

