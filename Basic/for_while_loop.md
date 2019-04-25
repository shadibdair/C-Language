## for / while
```
#include <iostream>
#include <array>

using namespace std;

int main()
{
	int choice=10;
	int arr[] = { 10,30,1,4,32,9 };

	for (int i = 0; i < size(arr); i++)
	{
		cout << arr[i] << endl;
	}

	cout << "1. order food " << endl;
	cout << "2. Sushi" << endl;
	cout << "3. Pizza" << endl;
	cout << "4. exit!!" << endl;

	while (choice != 3)
	{
		cin >> choice;
	}
	cout << "end of the loop" << endl;

	getchar();
	getchar();
}

/*
OUTPUT:

10
30
1
4
32
9
1. order food
2. Sushi
3. Pizza
4. exit!!

*/
```