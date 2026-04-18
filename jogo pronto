#include <stdio.h>

// Move a torre N casas para a direita
void moverTorre(int casas) {
    if (casas == 0) return;
    printf("Direita\n");
    moverTorre(casas - 1);
}

// Move a rainha N casas para a esquerda
void moverRainha(int casas) {
    if (casas == 0) return;
    printf("Esquerda\n");
    moverRainha(casas - 1);
}

// Move o bispo N casas na diagonal (cima + direita)
void moverBispo(int casas) {
    if (casas == 0) return;
    printf("Cima\nDireita\n");
    moverBispo(casas - 1);
}

int main() {
    printf("Movimento da Torre:\n");
    moverTorre(5);

    printf("\nMovimento do Bispo:\n");
    moverBispo(5);

    printf("\nMovimento da Rainha:\n");
    moverRainha(8);

    // Cavalo: 2 casas para cima, 1 para a direita
    printf("\nMovimento do Cavalo:\n");
    for (int i = 0; i < 2; i++)
        printf("Cima\n");
    printf("Direita\n");

    return 0;
}
