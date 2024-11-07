#include <stdio.h>
#include <string.h>

int main() {
    char str[100];

    printf("Digite uma string: ");
    fgets(str, sizeof(str), stdin); // Leitura da string

    // Remover o caractere de nova linha se presente
    str[strcspn(str, "\n")] = '\0';

    printf("Conteúdo da string: %s\n", str);
    printf("Comprimento da string: %lu\n", strlen(str));

    return 0;
}
