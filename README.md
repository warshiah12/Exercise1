# Exercise1
C++basic programming
#include<iostream>
using namespace std;
int main()
{
	int value;
	cout << "Enter the value of your own choice : " << endl;
	cin >> value;
	if (value % 2 == 0)
	{
		cout << "It is an even number!" << endl;
	}
	else
	{
		cout << "It is an odd number!" << endl;
	}
	return 0;
}
