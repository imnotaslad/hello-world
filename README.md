# hello-world
Just another repository

#include "pch.h"
#include <iostream>
#include <cstdlib>
#include <cmath>

using namespace std;

int inputS()
{
	setlocale(LC_ALL, "Rus");
	int Sq;
	cout << "введите сажени: " << endl;
	cin >> Sq;
	return Sq;
}
int inputA()
{
	setlocale(LC_ALL, "Rus");
	int Ar;
	cout << "введите аршины: " << endl;
	cin >> Ar;
	return Ar;
}
int main()
{
	int S = inputS();
	int A = inputA();
	double dm(int S, int A);
	double m;
	m = (S + A / 3)*2.16;
	cout << "расстояние в метрах: " << m;
	return m;

}
