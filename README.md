# if the marks obtained by a student in five different subjects are input through keyboard, write a program to find out the aggregate marks and percentage marks obtained by the student.Assume that maximum marks that can be obtained by student in each subject is 100.


#include&lt;stdio.h>

int main()

{
float math,phy,chem,os,java; 

printf("Enter maths marks\n");

scanf("%f",&amp;math); 

printf("Enter physics marks\n"); 

scanf("%f",&amp;phy);

printf("Enter chemistry marks\n");

scanf("%f",&amp;chem);

printf("Enter opearting system marks\n");

scanf("%f",&amp;os);

printf("Enter java marks\n");

scanf("%f",&amp;java); 

float aggregate,percentage;

aggregate=(math+phy+chem+os+java)/5; 

percentage=(math+phy+chem+os+java)*0.2; 

printf("The Aggragate marks are %.1f\n",aggregate); 

printf("The Percentage marks are %.1f\n",percentage);


}
