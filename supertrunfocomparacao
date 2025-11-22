#include <stdio.h>

int main() {

char estado1;  
char nome1[50];
float populacao1;
float area1;
float pib1;
int turistico1;
float densidade1;
float pibc1;
float super1

printf("digite a letra do estado\n");
scanf(" %c", &estado1);
while (getchar() != '\n');   // esvazia o buffer

printf("digite o nome do estado\n");
scanf("%s", nome1);
while (getchar() != '\n');   // esvazia o buffer

printf("digite a populaçao\n");
scanf("%f", &populacao1);

printf("digite a area\n");
scanf("%f", &area1);

printf("digite o pib\n");
scanf("%f", &pib1);

printf("digite o ponto turistico\n");
scanf("%d", &turistico1);

densidade1 = populacao1 / area1;
pibc1 = pib1 / populacao1;

// Cálculo do Super Poder
super1 = (float)populacao1 + area1 + pib1 + turistico1 + pibc1 + (1.0 / densidade1);

// ==== CARTA 2 ====

char estado2;
char nome2[50];
float populacao2;
float area2;
float pib2;
int turistico2;
float densidade2;
float pibc2;
float super2

 // Cálculo do Super Poder
 super2 = (float)populacao2 + area2 + pib2 + turistico2 + pibc2 + (1.0 / densidade2);
printf("digite a letra do estado\n");
scanf(" %c", &estado2);
while (getchar() != '\n');   // esvazia o buffer
printf("digite o nome do estado\n");
scanf("%s", nome2);
while (getchar() != '\n');   // esvazia o buffer

printf("digite a populaçao\n");
scanf("%f", &populacao2);

printf("digite a area\n");
scanf("%f", &area2);

printf("digite o pib\n");
scanf("%f", &pib2);

printf("digite o ponto turistico\n");
scanf("%d", &turistico2);

densidade2 = populacao2 / area2;
pibc2 = pib2 / populacao2;


// ===== RESULTADOS =====

printf("\n=== CARTA 1 ===\n");
printf("Estado: %c\n", estado1);
printf("Nome: %s\n", nome1);
printf("Populacao: %.2f\n", populacao1);
printf("Area: %.2f\n", area1);
printf("PIB: %.2f\n", pib1);
printf("Pontos Turisticos: %d\n", turistico1);
printf("Densidade: %.2f\n", densidade1);
printf("PIB per capita: %.2f\n", pibc1);


printf("\n=== CARTA 2 ===\n");
printf("Estado: %c\n", estado2);
printf("Nome: %s\n", nome2);
printf("Populacao: %.2f\n", populacao2);
printf("Area: %.2f\n", area2);
printf("PIB: %.2f\n", pib2);
printf("Pontos Turisticos: %d\n", turistico2);
printf("Densidade: %.2f\n", densidade2);
printf("PIB per capita: %.2f\n", pibc2);

printf("\n===== COMPARAÇÃO DE CARTAS =====\n\n");

 printf("Populacao: Carta 1 venceu (%d)\n", populacao1 > populacao2);
    printf("Area: Carta 1 venceu (%d)\n", area1 > area2);
    printf("PIB: Carta 1 venceu (%d)\n", pib1 > pib2);
    printf("Pontos Turisticos: Carta 1 venceu (%d)\n", turistico1 > turistico2);

    // Menor densidade vence
    printf("Densidade Populacional: Carta 1 venceu (%d)\n", densidade1 < densidade2);

    printf("PIB per Capita: Carta 1 venceu (%d)\n", pibc1 > pibc2);
    printf("Super Poder: Carta 1 venceu (%d)\n", super1 > super2);


return 0;

}
