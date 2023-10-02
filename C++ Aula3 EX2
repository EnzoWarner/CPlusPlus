#include <cstdlib>
#include <iostream>
using namespace std;
int main(int argc, char *argv[])
{
   setlocale(LC_CTYPE, "portugues_brazil");
    int i, j;
    float matrizA[3][5], Soma_Linha[3] = {0};
    for (i = 0; i < 3; i++) {
        for (j = 0; j < 5; j++) {
            cout << "Insira o valor para posição (" << i << "," << j << "): ";
            cin >> matrizA[i][j];
            Soma_Linha[i] += matrizA[i][j];
        }
    }
    for (i = 0; i < 3; i++) {
        cout << "Soma da linha " << i << ": " << Soma_Linha[i] << endl;
    }
    system("PAUSE");
    return 0;
}
