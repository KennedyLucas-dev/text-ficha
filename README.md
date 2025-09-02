#include <stdio.h>

int main() {
    int idade, matricula;
    float altura;
    char aluno[50];
    
    printf("Digite sua idade: ");
    scanf("%d", &idade);
    
    printf("Digite sua altura: ");
    scanf("%f", &altura);
    
    printf("Digite o nome do aluno: ");
    scanf("%s", aluno);  // sem o &
    
    printf("Digite sua matricula: ");
    scanf("%d", &matricula);
    
    printf("\n--- Dados do Aluno ---\n");
    printf("Aluno: %s\n", aluno);
    printf("Matricula: %d \n", matricula);
    printf("Idade: %d anos\n", idade);
    printf("Altura: %.2f m\n", altura);
    
    return 0;
}
