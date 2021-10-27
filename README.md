# Lecture-5_Exercises

// Biography
#include <iostream> 
using namespace std;

int main()
{
	cout << "What is your name?" << endl;
	string name, home, age;
	cin >> name;
	cout << "Nice to meet you " << name << "!" << endl;
	cout << "Where are you from?" << endl;
	cin >> home;
	cout << "That's awesome! I've always wanted to go to " << home << "!" << endl;
	cout << "How old are you?" << endl;
	cin >> age;
	cout << "That's cool! Very nice to meet you again!!!\n";
	return 0;
}
----------------------------------------------------------------------------------------------------
// Temperature_Celsius 2 Fahrenheit
#include <iostream>
using namespace std;

int main()
{
	cout << "Please enter a temperature in Celsius" << endl;
	int temp;
	cin >> temp;
	cout << temp << " " << "degrees Celsius is " << (temp * 9/5) + 32 << " " << "degrees in Fahrenheit." << endl;
	return 0;

}
-------------------------------------------------------------------------------------------------------------------------
// Temperature_Fahrenheit 2 Celsius
#include <iostream>
using namespace std;

int main()
{
	cout << "Please enter a temperature in Fahrenheit" << endl;
	int temp;
	cin >> temp;
	cout << temp << " " << "degrees Fahrenheit is " << (temp - 32) * (0.556) << " " << "degrees in Celsius." << endl;
	return 0;

}
--------------------------------------------------------------------------------------------------------------------------
// Circles
#include <iostream>
using namespace std;

int main()
{
	cout << "Please enter the radius of the circle" << endl;
	double r, a, c;
	cin >> r;
	a = 3.14 * r * r;
  c = 2 * 3.14 * r;
	cout << "The area of your circle is " << a << endl;
	cout << "The circumference of your circle is " << c << endl;
	return 0;
}
---------------------------------------------------------------------------------------------
// Area
#include <iostream>
using namespace std;

int main()
{
	cout << "Please enter a length and width for a rectangle, square, and triangle (length first then width)" << endl;
	double l, w, rectangle, square, triangle;
	cin >> l >> w;
	rectangle = w * l;
	square = l * l;
	triangle = w * l * 0.5;
	cout << "The area of a rectangle is " <<rectangle << endl;
	cout << "The area of a square is " <<square << endl;
	cout << "The area of a triangle is " << triangle << endl;
	return 0;
}
