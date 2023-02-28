#include<stdio.h> 
#include<math.h> 
#include<locale.h> 
int main () 
{ 
setlocale(LC_ALL,"Rus"); 
 
float h=3,x,y,s; 
 
printf ("Введите x->"); 
scanf ("%f",&x); 
 
y=pow(x,2)+h;
 
printf("Х равен = %f",y); 
getchar(); 
}
