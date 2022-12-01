# XOR
#include <iostream>
using namespace std;
int хоr(bool p, bool q);

int main()
{
	setlocale(LC_ALL, "Russian");
	bool p, q;
	cout << "Введите P (0 или 1): ";
	cin >> p;
	cout << "Введите Q (0 или 1): ";
	cin >> q;
	cout << "P XOR Q: " << хоr( p, q) << '\n';
	return 0;
}
int хоr(bool p, bool q)
{
	return (p || q) && !(p && q);
}
