# projetogitteste
teste de aula
//Projeto em C

#include <stdio.h>
int main()
{
int peso;
  float altura, imc;

  printf("Informe o peso (em kgs):");
  scanf("%d", &peso);

  printf("Informe a altura (em metros)Ex: 1.8 :");
  scanf("%f", &altura);

  imc = peso / (altura * altura);

  printf("IMC = %.2f\n", imc);
  if (imc < 18.5)
     printf("Abaixo do peso!");
  else if ((imc >= 18.5) && (imc < 25))
          printf("Peso ideal!");
       else if ((imc >= 25) && (imc < 30))
               printf("Acima do peso!");
            else if ((imc >= 30) && (imc < 34))
                    printf("Obeso!");
		 else
		    printf("É bom se cuidar");


return 0;
}
