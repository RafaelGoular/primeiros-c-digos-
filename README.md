#include <iostream>
using namespace std;

int main () {
	float Idade, Aula, Dia, Resposta;
	//Coleta de dados do candidato
	cout << "Quntos anos tem a sua Mãe?";
	cin >> Idade;
	cout << "Quanta Aulas ela teve na vida?";
	cin >> Aula;
	cout << "Qual o dia que ela teve?";
	cin >> Dia;
	// Forma de calcular 
	Resposta = Idade*Aula*Dia;
	// Demonstração do resultdo
	cout << "Multiplicação dos dados:" << Resposta;
	
	
}
