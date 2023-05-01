#include <stdio.h>
#include <math.h>

int main()
{
    int a, b, c;
    int opcao =-1;
    float xl, xll, bl, bll, delta, deltal, base, rd;
    do {
        printf("O que vc deseja fazer:\n");
        printf("1 - Calcular\n");
        printf("0 - Sair\n");
        scanf ("%i", &opcao);

        if (opcao==1){
                printf ("Digite o valor de a, b e c, respectivamente:\n");
                scanf ("%i %i %i", &a, &b, &c);
                bll = b*b;
                bl = b * -1;
                deltal = -4 * a * c;
                delta = bll + deltal;
                rd = sqrt(delta);
                base = 2 * a;
                xl = (bl + rd) / base;
                xll = (bl - rd) / base;
                printf("O valor de xl e': %f\ ", xl);
                printf("O valor de xll e': %f\ ", xll);

        }

    }while (opcao !=0);

    return 0;
}
