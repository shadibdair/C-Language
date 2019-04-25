## Switch case !
```
#include <iostream>
#include <array>

using namespace std;

int main()
{
	int myFav = 0;

	cout << "Welcome Welcome !! " << endl;
	int choose = 0;
	char list[4][9] = {"football", "music","dance","eat"};
	cout << "what you prefer to do ??" << endl;
	cout << "choose one -- please enter the number: " << endl;

	for (int i=0; i < size(list); i++)
	{
		cout <<list[i] << endl;
	}
	cout << "-----------------------------------------------" << endl;
	cin >> myFav;

	switch (myFav)
	{
	case 1: cout << list[0] << endl;
		cout << "you are the best player in the world!!" << endl;
		break;
	case 2: cout << list[1] << endl;
		cout << "wish to you all the luck in your first song :)" << endl;
		break;
	case 3: cout << list[2] << endl;
		cout << "good dance!!" << endl;
		break;
	case 4: cout << list[3] << endl;
		cout << "You are my best Friend ;-)" << endl;
		break;
	default:
		break;
	}

	getchar();
	getchar();
}

/*
OUTPUT:

Welcome Welcome !!
what you prefer to do ??
choose one -- please enter the number:
football
music
dance
eat
-----------------------------------------------
1
football
you are the best player in the world!!
*/
```