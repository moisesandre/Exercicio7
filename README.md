# Exercicio7

#include <stdio.h>
#include <stdlib.h>

int main()
{
    system("color 0b");
    int i, n[10], q;

    for (i=0; i<=9; i++)
    {
        printf("Digite um numero: ");
        scanf("%d", &n[i]);
    }

    for (i=0; i<=9; i++)
    {
        q=n[i]*n[i];
        printf("O quadrado de %d e %d\n",n[i],q);
    }

    return 0;
}
