#include <cstdlib>
#include <iostream>
#include <math.h>
/* 2- Fazer um programa que digite vários números no vetor de 
tamanho máximo de 100 elementos, até digitar o número "0". 
Imprimir quantos números iguais ao último número foram lidos. 
O limite de números é 100.  Sem considerar o "0" como último 
número. */
 using namespace std;
int main(int argc, char *argv[]) {
	setlocale(LC_CTYPE, "portuguese_brazil");
	float elementos[100];
	int i=0,j,n=1,cont=0;
	while(n!=0 && i<100) {
		cout<<"Insira 100 numeros: ";
		cin>>n;
		cout<<"\n";
		if(n!=0) {
			elementos[i]=n;
			i++;
		}
	}
	for(j=0;j<i-1;j++) {
		if(elementos[j]==elementos[i-1]) {
			cont++;	
		}
	}
	cout<<cont<<"\n";
	system("PAUSE");
	return 0;
}
