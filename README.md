# Programando_em_C_2
Criando um sistema em C que pga o valor digitidado pelo usuario e mostra se  ele é menor de idade, adulto  ou idoso

Codigo 100% funcional

// Desenvolvedor.: Adalberto Fernnandes
// Aprendendo.:  if, else, else if
// Sistema Versão.: v1.0
// Estrutura de Decisão if, else, else if
#include<stdio.h>
#include<stdlib.h>
#include<locale.h>

int main(){
	setlocale(LC_ALL,"Portuguese");
	
	int idade = 0;
	
	printf("Qual a sua idade: ");
	scanf("%d", &idade);
	
	if(idade < 18){
		printf("Você é menor de idade \n");
	}else if (idade > 18 && idade < 60){ //As duas condinções deverá ser verdadeira.
		printf("Você é Adulto \n");
	}else{
		printf("Você é idoso! \n");
	}
	// Saída
	printf("Sua idade é %d", idade);
		
	return 0;
}
