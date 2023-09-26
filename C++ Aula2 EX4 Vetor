#include <cstdlib>
#include <iostream>
#include <math.h>
/* 4-) Ler um vetor V de 10 elementos e obter um vetor W cujos 
componentes são os fatoriais dos respectivos componentes de V. */
using namespace std;
int fatorial(int n) {
    if (n <= 1) {
        return 1;
    }
    return n * fatorial(n - 1);
}
int main(int argc, char *argv[]) {
	setlocale(LC_CTYPE, "portuguese_brazil");
	long v[10],w[10];
	int i,j;
	
	for(i=0;i<10;i++){
		cout<<"Insira o "<<i+1<<"º numero: ";
		cin>>v[i];
	}
	// Calcular os fatoriais e preencher o vetor W
    for (i = 0; i < 10; i++) {
        w[i] = fatorial(static_cast<int>(v[i]));
    }
     cout << "Vetor W (fatoriais dos elementos de V): ";
    for (i = 0; i < 10; i++) {
        cout << w[i] << " ";
    }
    cout << endl;
    system("PAUSE");
    return 0;
}
