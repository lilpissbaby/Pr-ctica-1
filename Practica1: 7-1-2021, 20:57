#include <stdio.h>
#include <string.h>

#define MAXIMO_CHARS_FRASE 50

int main()
{   
    char frase_guardada[MAXIMO_CHARS_FRASE];
    char frase_modificada[15][MAXIMO_CHARS_FRASE]; //El máximo de palabras es 15, así que el número de filas también será 15
    FILE* nombre_fichero;
    char yodatest[MAXIMO_CHARS_FRASE]; //Corresponde al archivo del que se sacarán las frases
    char apertura_fichero; //Declaración de la función, aunque queda por ver si con "char" es correcto declararla o no
    
    
    apertura_fichero = fopen(yodatest, "r"); //Si en la línea 12 no se declaraba la función con "char", daba error
    if(apertura_fichero != NULL){
      
      
            //PROCEDIMIENTO PARA PEDIR VELOCIDAD Y YODIFICACIÓN AL USUARIO
      
      int velocidad_habla;
      int coeficiente_yodif;
       
       printf("Quina serà la velocitat de parla? \nRecorda: ha de ser entre 0 i 2:\n "); //De 0 a 2
       scanf("%d",&velocidad_habla);
       
       switch(velocidad_habla){
           case 0:
            printf("\n\nCoeficient yodificació? \nTambé serà d'1 a 2:\n "); //De 0 a 2
            scanf("%d",&coeficiente_yodif);
            break;
            
           case 1:
            printf("\n\nCoeficient yodificació? \nTambé serà d'1 a 2:\n  "); //De 0 a 2
            scanf("%d",&coeficiente_yodif);
            break;
            
           case 2:
            printf("\n\nCoeficient yodificació? \nTambé serà d'1 a 2:\n  "); //De 0 a 2
            scanf("%d",&coeficiente_yodif);
            break;
            
           default:
            printf("\nVelocitat incorrecte, i per tant:\n");
       }
       
       switch(coeficiente_yodif){
           case 0:
            printf("correcte");
            break;
            
           case 1:
            printf("correcte");
            break;
            
           case 2:
            printf("correcte");
            break;
            
           default:
            printf("\nYodificació incorrecte");
            
            
       }
        
    }
    else{
        printf("No se pudo abrir el fichero\n");
    }
    
    
    
    
    return 0;
}
