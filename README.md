#include<stdio.h>
#include<stdlib.h>
#include<conio.h>
int main
{
int num,sumaNum=0,i=0,conteo
 printf("\nPrograma num divisibles entre nueve /n");
    do
{
    printf("\n Ingrese numero %i\t");
    scanf("%i",&num);
    while(num<0)
{
    printf("\n Volver a ingresar numero\t");
    scanf("%i",&num);
}
    printf("\n Desea ingresar otro num? 1 para si\n");
    scanf("%i",&conteo);
    i++;
    if(num%9==0)
    sumaNum=num+sumaNum;
}
    while(conteo==1);
    printf("\n La suma es %d\n",sumaNum);
    getch();
    return 0;
}
