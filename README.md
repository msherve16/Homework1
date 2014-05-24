									Homework1
=========
//////////////////////
// Morgan Sherve
// May 21, 2014
//First Assignment
////////////////////

#include <iostream>
#include <string>
using namespace std;

void ex02()
{
	int hasPassedTest = true;
	int x = rand() % 100;
	int y = rand() % 100;
	int numberOfShares;
	int boxWidth;
	int bookWidth;
	int shelfLife;
	int temperature;
	int newShelfLife;
	
	cout << " Enter number of shares: " << endl;
	cin >> numberOfShares;
	if (numberOfShares < 100)
		{cout << "Number of Shares is less than 100." << endl;}
	else 
		{cout << "Number of Shares is not less than 100." << endl;}
	
	if (x >= y)
		{ cout << x << " is greater than or equal to " << y << endl;}
	else
		{cout << x << "is not greater than " << y << endl;}
	
	cout << " Please enter Box width: " << endl;
	cin >> boxWidth;
	cout << " Please enter Book width: " << endl;
	cin >> bookWidth;
	if (boxWidth% bookWidth == 0)
		{cout << " Box width is divisible by Book width." << endl;}
		
	cout << "Shelf life of chocolates: " << endl;
	cin >> shelfLife;
	cout << "Temperature: " << endl;
	cin >> temperature;
	if (temperature > 90)
		{newShelfLife == (shelfLife - 4);}

}

void ex03()
{
	int squareArea;
	char response;
	string mailingAddress;

	cout << "Enter Area of Square: " << endl;
	cin >> squareArea;
	cout << sqrt(squareArea)*(sqrt (2));

	cout << "Please enter y/n: " << endl;
	cin >> response;
	if (response = 'y')
		{cout << "yes" << endl;}
	else if (response = 'n'}
		{cout << "no" << endl;

	cout << "Mailing Address: " << endl;
	cin >> mailingAddress;

}

void ex04
{
	int num;
	int y=num;
	int x;
	do{
		cout << " Enter a number between one and ten: " << endl;
		cin << num;
	} while (num <1 || num > 10)
	int 
	do{
	
	}
	do{
		cout << "* ";
	} while ( y>= 1 && y<= num)
	
	
	for (x=1; x <=20; x++)
	{
	sum = 2*x;
	cout << sum << " ";
	}
	partF ();
}

int partF()
 {
	int x = rand() % 100;
	int y = rand() % 100;
 	int add = x+y;
 	cout << add;
 }
 
int partG(int n)
{
	int sum =0;
	for (int i = 1; i<=n; i ++)
		{sum += i;
		return sum;}
}

void ex(05)
{
	int val = 5;
	cont int m = 5;
	int values [m];
	while (val >= 0)
	{ 
		cout << "Please enter an integer: " << endl;
		cin >> m;
		val --;
	}
	int result = 0;
	for (int n = 0; n < m; n++)
		{result += values[n];}
}

int main ()
{
	ex02();
	ex03();
	ex04();
	ex05();
		return 0;
}
