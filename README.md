// Code to check if entered year is Leap-Year

#include<stdio.h>
int main(){
    int year;
    printf("Enter a year: ");
    scanf("%d", &year);

    if((year%4==0 && year%100 != 0) || year %400==0 ){  //main condition
        printf("It's a Leap Year");
    } else 
        printf("Not a Leap Year");
    return 0;
}
