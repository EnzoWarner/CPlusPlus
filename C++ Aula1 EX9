#include <iostream>
#include <locale> // Para setlocale
/* 9. Escreva um programa que solicite ao usuário quatro 
números e mostre na tela o maior, o menor e a média 
aritmética dos números digitados. */
using namespace std;
int main(int argc, char *argv[]) {
    setlocale(LC_CTYPE, "portuguese_brazil");
    float maior, menor, media, numero;
    int contador = 1;
    while (contador <= 4) {
        cout << "Insira os quatro números: ";
        cin >> numero;
        if (contador == 1) {
            maior = numero;
            menor = numero;
            media = numero; // Inicialização da média
        } else {
            if (numero > maior) {
                maior = numero;
            }
            if (numero < menor) {
                menor = numero;
            }
            media += numero; // Acumular os valores para o cálculo da média
        }
        contador++;
    }
    media /= 4; // Dividir a soma acumulada pelos 4 números para obter a média
    cout << "O menor número é: " << menor << "\nO maior número é: " << maior << "\nA média é: " << media << endl;
    system("PAUSE");
    return 0;
}
