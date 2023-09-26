#include <cstdlib>
#include <iostream>
#include <math.h>
/* 1- Fazer um programa que leia vários números inteiros 
e positivos. A leitura se encerra quando encontrar um número 
negativo ou quando o vetor ficar completo. Sabe-se que o 
vetor possui, no máximo, 10 elementos. Gerar e imprimir um 
vetor onde cada elemento é o inverso do correspondente do 
vetor original. */
 using namespace std;
int main(int argc, char *argv[]) {
	setlocale(LC_CTYPE, "portuguese_brazil");
	float elementos[10];
	int i=0,j,n;
	do {
		cout<<("Insira dez numeros: ");
		cin>>n;
		cout<<"\n";
		if(n>=0) {
			elementos[i] = n;
			i++;
		}
		else {
			cout<<"finalizando"<<endl;
			break;
		}
	}
	while(i<10&&n>0);
	for(j=10-1;j>=0;j--) {
		cout<<elementos[j] << " ";
	}
	cout<<endl;
	system("PAUSE");
	return 0;
}
