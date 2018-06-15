## University of Missouri

### College of Business

![College of Business](https://mizzouadvantage.missouri.edu/wp-content/uploads/2015/10/MIZ-BIZ.jpg)

#### *Programs Offered*:
* [Accountancy](accounting.cd)
* [Economics](https://business.missouri.edu/programs-and-admissions/undergraduate/degree-programs/economics "Mizzou Economics")
* [Finance](https://business.missouri.edu/programs-and-admissions/undergraduate/academics/finance-and-banking "Mizzou Finance")
* [International Business](https://business.missouri.edu/programs-and-admissions/undergraduate/degree-programs/international-business "Mizzou International Business")
* [Management](https://business.missouri.edu/programs-and-admissions/undergraduate/degree-programs/management "Mizzou Management")
* [Marketing](https://business.missouri.edu/programs-and-admissions/undergraduate/degree-programs/marketing "Mizzou Marketing")
* ~~Real Estate~~


#### Grade Calculator

```
#include <stdio.h>
int main(void)
{
        int grade;
        printf("Enter your percentage (0-100):");
        scanf("%i", grade);
        while(grade<0 || grade>100)
        {
                printf("Invalid percentage. Enter your percentage (0-100):");
                scanf("%i", grade);
        }
        if(grade>=90)
                printf("You got an A");
        else if(grade<90 && grade>=80)
                printf("You got a B");
        else if(grade<80 && grade>=70)
                printf("You got a C");
        else if(grade<70 && grade>=60)
                printf("You got a D");
        else printf("You got a F");
return 0;
}
```
