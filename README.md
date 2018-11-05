# C
#include <stdio.h>
#include <stdlib.h>

int main()
{
    char name;
    int currentYear = 2018;
    int birthYear;
    int age;
    age = currentYear - birthYear;



    printf("what is your name\n");
    scanf("%s", name);
    printf("welcome %s \n",name);

    printf("%s enter you birth year\n");
    scanf("%d" , birthYear);


    printf("%s you are %d years old \n", name, age);
    return 0;
}
