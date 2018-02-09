#include <iostream>
using namespace std;
int main()

// jadziem z kalkulatorem


{
	double a;				//definiujemy a i b- póki co będziemy na nich bazować
	double b;				//kalkulator będzie dwuliczbowy

	cout << "Jakie dzialanie chcesz wybrac? \n";
	cout << "\n 1- dodawanie \n 2- odejmowanie \n 3- mnozenie \n 4- dzielenie \n\n";
	
	int dzialanie;
	cin >> dzialanie;
		switch (dzialanie) {
					case 1: //dodawanie
					cout << "podaj a = \n";
					cin >> a;
					cout << "podaj b = \n";
					cin >> b;
					cout << "\n wynik to:" << a + b << "\n";
					break;

					case 2: //odejmowanie
					cout << "podaj a = \n";
					cin >> a;
					cout << "podaj b = \n";
					cin >> b;
					cout << "\n wynik to:" << a - b << "a-b\n";
					break;

					case 3: //mnozenie
					cout << "podaj a = \n";
					cin >> a;
					cout << "podaj b = \n";
					cin >> b;
					cout << "\n wynik to:" << a * b << "a * b\n";
					break;

					case 4: // dzielenie
					cout << "podaj a = \n";
					cin >> a;
					cout << "podaj b = \n";
					cin >> b;
					cout << "\n wynik to:" << a / b << "a / b \n";
					break;

					default:
					cout << "nie ma takiego numeru... \n";
					break;

					}
	system("pause");
		}
