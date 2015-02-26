# wsq07.cpp

/*
#WSQ07
Main: Sum of numbers
By: Jorge Cervantes
#TC1017
Referencia: XXXXXXXXXXX
---------------------------------------------------------------------
*/

#include <iostream>
#include <string>
using namespace std;

int main(){

int numero1, numero2, total = 0, numeroA, numeroB;

	cout << "Introduce el numero (menor)\n";
	cin >> numero1;
	numeroA = numero1;

	cout << "Introduce tu segundo numero (mayor)\n";
	cin >> numero2;
	numeroB = numero2;

	do{

numero1 = numero1 + 1;
total = total +numero1;

	}while(numero1 <= numero2);

	cout << "La sume de " <<numeroA<< " a " <<numeroB<< " es de " <<total;
	cout << "\n";

return 0;
}
