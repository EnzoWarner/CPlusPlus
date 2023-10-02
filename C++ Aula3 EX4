#include <cstdlib>
#include <iostream>

using namespace std;
/* 4-) Criar uma matriz de ordem 5 e imprima: toda a matriz e 
depois os números que se encontram em posições cuja a linha 
mais a coluna formam um número ímpar. */
int main(int argc, char *argv[])
{
    setlocale(LC_CTYPE, "portuguese_brazil");
    int i,j;
    float matriz[5][5],cont[5][5] = {0}; // Inicializa cont com 0
    // Inicializa a matriz com valores inseridos pelo usuário
    for(i=0;i<5;i++){
    for(j=0;j<5;j++){
    cout<<"Insira os numeros da posição("<<i<<","<<j<<"): ";
    cin>>matriz[i][j];
    if((i+j) % 2 != 0) {
    	cont[i][j] = matriz[i][j];
	}
}
}
    cout<<"\nA matriz é:\n\n";
    for(i=0;i<5;i++){
    for(j=0;j<5;j++){
    cout<<matriz[i][j]<<"\t";
}
    cout<<endl;
}  
    cout << "\nOs números nas posições cuja linha + coluna formam um número ímpar:\n\n";
    for(i=0;i<5;i++) {
    	for(j=0;j<5;j++) {
    		if(cont[i][j] != 0){
    			cout << cont[i][j] << "\t";
			}
			else{
			    cout << "-\t"; // Mostra '-' para posições onde não há número ímpar
			}
		}
		cout<<endl;
	}
	system("PAUSE");
    return EXIT_SUCCESS;
}
