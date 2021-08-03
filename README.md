# Verificacao-de-Gabarito-C
#include <stdio.h>
#include <stdlib.h>

int main()
{

    int  ra = 0, x, b = 0, c, nota = 0, y = 0, d;
    int Frequencia[11]= {0};
    float media, ntm, alunos = 0, notam, notag = 0;
    char G[10] = {'a','b','c','d','e','a','b','c','d','e'};
    char R[10];
    while (b == 0){
            nota = 0;
            printf("=====================\n");
        printf("RA:");
        scanf("%d", &ra);
        fflush(stdin);
        if(ra == 9999){
            break;
        }
    for (x = 0; x < 10; x = x + 1){
        printf("Resposta %d:", c = 1 + x);
        scanf("%c", &R[x]);
        fflush(stdin);
        if (R[x] == G[x]){
            nota++;}


    }
    alunos++;
    notag = notag + nota;
    if (nota >= 5){
        ntm++;}
    Frequencia[nota] ++;
    printf("\n\nRA:%d", ra);
    printf("      Nota:%d\n", nota);
    }
    for (x = 0; x < 11; x++){
        if (Frequencia[x] > y){
            y = Frequencia[x];
            d = x;

        }
    }
    notam = notag / alunos;
    media = (ntm * 100) / alunos;
    printf("            Relatorio Final   \n");
    printf("======================================\n");
    printf("Porcentagem de Aprovacao:...: %.2f %%\n", media);
    printf("Nota com maior frequencia:..: %d\n", d);
    printf("Nota Media:.................: %.2f", notam);
    printf("\n\n\n\n\n");


    return 0;
}
