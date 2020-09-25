//Circuitos-1

#include <stdio.h>

int main (){

    float V; //valor de la fuente en volts
    int R1, R2, R3; //valor de las resistencias
    float I1,I2, I3; // valor de la corriente en cada resistencia

    printf ("Escribe el valor de la fuente V: ");
    scanf("%f",&V);

    printf("El valor debe ser escrito en notacion completa no usar prefijos\n");
    printf ("Resistencia 1: ");
    scanf("%d", &R1);
    printf ("Resistencia 2: ");
    scanf("%d", &R2);
    printf ("Resistencia 3: ");
    scanf("%d", &R3);

    I1= V/R1;
    I2= V/R2;
    I3= V/R3;

    printf("La corriente I1 es %0.3fA\n",I1);
    printf("La corriente I2 es %0.3fA\n",I2);
    printf("La corriente I3 es %0.3fA\n",I3);
    printf("El voltaje en R1 es %0.3fV\n", V);
    printf("El voltaje en R2 es %0.3fV\n", V);
    printf("El voltaje en R3 es %0.3fV\n", V);

    }


