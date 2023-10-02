#include <cstdlib>
#include <iostream>
#include <math.h>
/* 6-) Criar um vetor com a 8 elementos e ordená-los. */
using namespace std;
int main(int argc, char *argv[]) {
    setlocale(LC_CTYPE, "portuguese_brazil");
    float v[8];
    int i, j; 
    for (i = 0; i < 8; i++) {
        cout << "Insira o " << i + 1 << "º número: ";
        cin >> v[i];
    }
    for (i = 0; i < 7; i++) {
        for (j = 0; j < 7 - i; j++) {
            if (v[j] > v[j + 1]) {
                float temp = v[j];
                v[j] = v[j + 1];
                v[j + 1] = temp;
            }
        }
    }
    cout << "\nVetor ordenado:\n";
    for (i = 0; i < 8; i++) {
        cout << v[i] << "\t";
    }
    cout << endl;
    system("PAUSE");
    return 0;
}
