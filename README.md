# atividade-12-Iot

#include <stdio.h>

int main() {
    
    float numero1;
	float numero2;
    
    printf("Escreva o primeiro numero");
    scanf("%f", &numero1);
    
    printf("Escreva o segundo numero");
    scanf("%f", &numero2);
    
    float soma = numero1+numero2;
    
	if(soma< 0){
	printf("nao e possivel calcular esta soma.");
	}
    else{
    	printf("A soma desses numeros e: %.2f",soma);
	}
	
    return 0;
}
