#include <cstdlib>
#include <iostream>
#include <math.h>
/* 5-) Criar um programa que leia dados de um vetor de 12 elementos 
inteiros. Imprima o maior e menor sem ordenar, o percentual de 
números pares e a média dos elementos do vetor. */
using namespace std;
int main(int argc, char *argv[]) {
	setlocale(LC_CTYPE, "portuguese_brazil");
	int v[12];
    int i,media, soma = 0, maior, menor, pares = 0;
 	 for (i = 0; i < 12; i++) {
        cout << "Insira o " << i + 1 << "º número: ";
        cin >> v[i];
        soma = soma + v[i];
        if (i == 0) {
            maior = v[i];
            menor = v[i];
        }
        if (v[i] > maior) {
            maior = v[i];
        }
        if (v[i] < menor) {
            menor = v[i];
        }
        if (v[i] % 2 == 0) {
            pares++;
        }
    }
	media = soma/12;
	cout<<"O maior: "<<maior<<"\n O menor: "<<menor<<"\n Os percentual de numeros pares: "<<pares<<"\n A média: "<<media<<endl;
	system("PAUSE");
	return 0;
}
