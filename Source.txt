include<iostream>
#include<conio.h>

#include<string>
using namespace std;
void main() {
	int year[5], num[5], x;
	for (int i = 0; i < 5; i++)
	{
		cout << " Enter a year :" << i + 1 << endl;
		cin >> year[i];
		cout << " Enter a number of student " << endl;
		cin >> num[i];
	}
	cout << " Enter a number of students enrolled in current year : ";
	cin >> x;
	for (int i = 0; i < 5; i++) {
		cout << endl<<" More student enrolled in year  : "<<year[i];
		cout <<endl<< x - num[i] << " student enrolled in  "<<year[i] ;

	}

	_getch();

}
