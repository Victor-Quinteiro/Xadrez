#include <stdio.h>

    void Movertorre(int casas)
    {
        if (casas > 0)
        {
            printf("Direita\n");
            Movertorre(casas - 1);
        }
    }

    void Moverbispo(int casas) 
    {
        if (casas <= 0) return; 
        for (int v = 0; v < 1; v++) 
        { 
            for (int h = 0; h < 1; h++) 
            {
                printf("Cima Direita\n");
            }
        }
    Moverbispo(casas - 1); 
    }

    void Moverrainha(int casas3)
    {
        if (casas3 > 0)
        {
            printf("Esquerda\n");
            Moverrainha(casas3 - 1);
        }
    }

    void Movercavalo(int movimentos) {
    for (int m = 0; m < movimentos; m++) 
    {  
        for (int passo = 1; passo <= 3; passo++) 
        { 
            if (passo <= 2) 
            {
                printf("Cima\n"); 
                continue;         
            }
            if (passo == 3) 
            {
                printf("Direita\n");
                break;               
            }
        }
    }
}

int main () {

    printf("\nTorre !\n");
    Movertorre(5);

    printf("\nbispo !\n");
    Moverbispo(5);
    
    printf("\nRainha !\n");
    Moverrainha(8);

    printf("\nCavalo !\n");
    Movercavalo(1);
    
    return 0;
}
