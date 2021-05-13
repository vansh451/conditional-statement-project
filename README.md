//conditional statement 
#include<stdio.h>
#include<conio.h>

int main(){
    int marks;
    printf("Enter the marks\n");
    scanf("%d",&marks);
    if(marks>=85 && marks<=100)
    {
        printf("Student get Grade A");
    }
    else if(marks>=70 && marks<85)
    {
        printf("Student get Grade B");
    }
    else if(marks>=55 && marks<70)
    {
        printf("Student get Grade C");
    }
    else if(marks>=40 && marks<=54)
    {
        printf("Student get Grade D");
    }
    else if(marks<40)
    {
        printf("Student get Grade F");
    }
    else 
    {
        printf("Invalid Marks");
    }

    return 0;
    

    
}
