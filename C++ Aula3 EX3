#include <cstdlib>
#include <iostream>
using namespace std;
int main(int argc, char *argv[])
{
    setlocale(LC_CTYPE, "portuguese_brazil");
    int i, j;
    float matriz[2][3];
    for (i = 0; i < 2; i++) {
        for (j = 0; j < 3; j++) {
            cout << "Insira o valor para posição(" << i << "," << j << "): ";
            cin >> matriz[i][j];
        }
    }
    cout << "\n Os valores trocados sao:\n";
    for (j = 0; j < 3; j++) {
        for (i = 0; i < 2; i++) {
            cout << matriz[i][j] << " ";
        }
        cout << endl;
    }
    system("PAUSE");
    return EXIT_SUCCESS;
}
