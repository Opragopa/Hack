#include<iostream>
#include "windows.h"
#include "cstdlib"
#include <ctime>

int main()
{
	setlocale(LC_ALL, "Russian");
	int i = 0;
	std::string loading = "#";
	srand(time(NULL));
	std::cout << "Взлом NASA";
	Sleep(2000);
	do
	{
		
		if (i >= 100)
		{
			system("cls");
			std::cout << "ИДЕТ ВЗЛОМ - ";
			std::cout << 100 << '%';
			break;
		}
		system("cls");
		std::cout << "ИДЕТ ВЗЛОМ - ";
		std::cout << i << '%';
		i += rand() % 5 + 1;
		std::cout << '\n' << loading;
		loading = loading + '#';
		Sleep(rand() % 1000 + 1);
	} while (true);
	std::cout << "\nВзлом завершен!";
}
