# tarea-con-do-while
suma de numero divisble entre 9
#include <stdio.h>
#include <stdlib.h>

int main ()
{
int comparar, div,sumanumeros=0, i=0, numero, cantidad;
char repetir;

printf("\nprograma suma de numeros\n");
printf("\ncantidad de numeros a sumar?\t");
scanf("%d", & cantidad);
do
{
printf ("\n Ingrese numero \n\t",i);
scanf ("%d", &numero);
while(!numero>0 && numero <10)
{
printf("\ningrese numero \n\t");
scanf("%d", & numero);
div=numero%9;
if (div==0)
{
printf("\nes divisible entre 9\n");

}
else
{
printf("\n no es divisible entre 9\n");

}

 fflush(stdin);
{

printf("\ndesea ingresar otro numero?s/n\t");
scanf("%c", & repetir);

}while(repetir=='s' || repetir =='S');

sumanumeros+=div;
    i++;

return 0;

}

