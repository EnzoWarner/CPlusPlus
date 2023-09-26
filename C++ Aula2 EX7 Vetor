#include <cstdlib>
#include <iostream>
#include <math.h>
/* 7-) Fazer um programa que, dados dois vetores de 7 posições 
cada, efetue as operações aritméticas básicas, indicadas por um 
terceiro vetor cujos dados também são fornecidos pelo usuário, 
gerando e imprimindo um quarto vetor. */
using namespace std;
int main(int argc, char *argv[]) {
    setlocale(LC_CTYPE, "portuguese_brazil");
    float v[7], v2[7], resultado[7];
    char operacoes[7];
    int i, j;
    // Ler os elementos do primeiro vetor
    cout << "Insira os 7 elementos do primeiro vetor:" << endl;
    for (i = 0; i < 7; i++) {
        cout << "V[" << i + 1 << "]: ";
        cin >> v[i];
    }
    // Ler os elementos do segundo vetor
    cout << "Insira os 7 elementos do segundo vetor:" << endl;
    for (i = 0; i < 7; i++) {
        cout << "V2[" << i + 1 << "]: ";
        cin >> v2[i];
    }
    // Ler as operações
    cout << "Insira as operações (+, -, *, /) para cada elemento:" << endl;
    for (i = 0; i < 7; i++) {
        cout << "Operações[" << i + 1 << "]: ";
        cin >> operacoes[i];
    }
    // Realizar as operações e preencher o vetor resultado
    for (i = 0; i < 7; i++) {
        switch (operacoes[i]) {
            case '+':
                resultado[i] = v[i] + v2[i];
                break;
            case '-':
                resultado[i] = v[i] - v2[i];
                break;
            case '*':
                resultado[i] = v[i] * v2[i];
                break;
            case '/':
                if (v2[i] != 0) {
                    resultado[i] = v[i] / v2[i];
                } else {
                    cout << "Divisão por zero encontrada. Resultado indefinido." << endl;
                    return 1;
                }
                break;
            default:
                cout << "Operação inválida." << endl;
                return 1;
        }
    }
    // Imprimir o vetor resultado
    cout << "Vetor resultado das operações:" << endl;
    for (i = 0; i < 7; i++) {
        cout << resultado[i] << " ";
    }
    cout << endl;
    system("PAUSE");
    return 0;
}
