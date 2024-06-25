# numero-inteiro-positivo-e-inteiro-negativo-linguagem-c-
# include <stdio.h>

float numeroInteiro(float num1){
    return num1;
}

float positivoNegativo(float num1){
    if (num1 > 0){
        return 1;
    }else if(num1 < 0){
        return 0;
    }
}


int main(){
    float num1;
    printf("Digite o numero Inteiro : \n");
    scanf("%f",&num1);
    
    float resultadoNumeroInteiro = numeroInteiro(num1);
    float resultadoPositivoNegativo = positivoNegativo(num1);
    
    printf("O seu numero digitado foi : \n %f \n",resultadoNumeroInteiro);
    printf("Numero inteiro retorno =\n 1 \n Numero negativo retorno = 0 \n  O seu numero teve retorno : \n %f",resultadoPositivoNegativo);
    
    
}
