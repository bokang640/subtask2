#include <iostream>
using namespace std;

int main()


{
int temperature1;
int temperature2;
int temperature3;

	cout << "Enter the first temperature ready";
	cin>>temperature1;
	cout << "Enter the second temperature ready";
	cin>>temperature2;
	
	
	if(temperature2 -temperature1>50)
	cout<<"reduce frier heat before taking third reading\n";
	else if (temperature2 -temperature1>10)
		cout<<"increase the frier heat before taking third reading\n";
	
	cout << "Enter the third temperature ready";
	cin>>temperature3;
	
	if(temperature3 >= 150 && temperature3<=190)
	cout<<"you may start frying the magwinya\n";
	else 
	cout<<"oil is not for frying\n";
	return 0;}
