#include <cstdlib>
#include <iostream>

using namespace std;
/* 5-) Ler os elementos de uma matriz de ordem 6 e imprima 
o produto dos elementos que estão abaixo da diagonal 
principal. */
int main(int argc, char *argv[]) {
    setlocale(LC_CTYPE, "portuguese_brazil");
    int i, j;
    long matriz[6][6], cont[6][6] = {0};
    // Preencher a matriz com valores inseridos pelo usuário
    for (i = 0; i < 6; i++) {
        for (j = 0; j < 6; j++) {
            cout << "Insira o número da posição (" << i << "," << j << "): ";
            cin >> matriz[i][j];
        }
    }
    // Calcular o produto dos elementos abaixo da diagonal principal
    for (i = 0; i < 6; i++) {
        for (j = 0; j < 6; j++) {
            if (i > j) {
                if (j == 0) {
                    cont[i][j] = matriz[i][j];
                } else {
                    cont[i][j] = cont[i][j - 1] * matriz[i][j];
                }
            }
        }
    }
    cout << "\nA matriz é:\n\n";
    for (i = 0; i < 6; i++) {
        for (j = 0; j < 6; j++) {
            cout << matriz[i][j] << "\t";
        }
        cout << endl;
    }
    cout << "\nO produto dos elementos abaixo da diagonal principal é:\n";
    for (i = 0; i < 6; i++) {
        for (j = 0; j < 6; j++) {
            if (i > j) {
                cout << cont[i][j] << "\t";
            } else {
                cout << "-\t";
            }
        }
        cout << endl;
    }
    system("PAUSE");
    return EXIT_SUCCESS;
}

