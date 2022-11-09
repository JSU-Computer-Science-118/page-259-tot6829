#include <iostream>
using namespace std;

int main()
{
	double a, b, c, x1, x2;
	double discriminant, firstRoot, secondRoot;

	cout << "Please enter the values of a, b, and c respectively" <<
		endl;
	cin >> a >> b >> c;

	discriminant = (pow(b,2)) - (4*a*c);

	if (a == 0)
	{
		cout << "Invalid Entry" << endl;
	}
	else if (discriminant == 0)
	{
		x1 = (-b) / (2 * a);
		cout << "The single (repeated) root is " << x1 << endl;
	}
	else if (discriminant > 0)
	{
		firstRoot = (-b + sqrt(discriminant)) / (2 * a);
		secondRoot = (-b - sqrt(discriminant)) / (2 * a);
		cout << "Two real roots" << endl;
		cout << "First root " << firstRoot << endl;
		cout << "Second root " << secondRoot << endl;
	}
	else if (discriminant < 0)
	{
		cout << "Complex roots " << endl;
	}
	return 0;
}
