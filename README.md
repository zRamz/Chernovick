# Chernovick
double f(double x, double c, double a, double b, double d,int input)
{
	cout << "1:a(sin(bx))^(c) + d" << endl;
	cout << "2:a(cos(bx))^(c) + d" << endl;
	cout << "3:a(cos(bx))^(c) + d" << endl;
	cout << "4:a(cos(bx))^(c) + d" << endl;
	cout << "5:a(cos(bx))^(c) + d" << endl;
	cout << "6:a(cos(bx))^(c) + d" << endl;
	cout << "7:a(cos(bx))^(c) + d" << endl;
	cout << "8:a(cos(bx))^(c) + d" << endl;
	cout << "Доступные функции:";
		cout << "Выберите тип функции " << endl;
	cin >> input;
	switch (input) {
	case 1:
		return pow(a*sin(b*x),c) +d;
	case 2:
		return pow(a*cos(b*x),c) + d;
	}

}

ХУЙ
