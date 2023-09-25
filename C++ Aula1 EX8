#include <iostream>
#include <math.h>
/* 8. Crie um programa que solicite ao usuário os três 
ângulos de um triângulo e informe se este é um triângulo 
equilátero, isósceles ou escaleno.*/
 using namespace std;
int main(int argc, char *argv[]) {
	setlocale(LC_CTYPE, "portuguese_brazil");
	int angulo1,angulo2,angulo3;
	cout<<"Insira os lados do triângulo: \n";
	cin>>angulo1>>angulo2>>angulo3;
	if (angulo1 + angulo2 + angulo3 == 180) {
	if (angulo1==angulo2 && angulo2==angulo3){
		cout<<" é um triângulo equilátero"<<endl;
	}
	else if (angulo1!=angulo2 && angulo2!=angulo3){
		cout<<" é um triângulo escaleno"<<endl;
	}
	else {
		cout<<" é um triângulo isósceles"<<endl;
	}
	}
	else {
		cout<<"não é um triângulo, Os ângulos fornecidos não formam um triângulo válido"<<endl;
	}
	system("PAUSE");
	return 0;
}
