# Largest-number-of-the-Three
#include<iostream>

 using namespace std;

 int main() {

	int num1,num2,num3;

	cout<<" Enter first number:";

	cin>>num1;

	cout<<" Enter second number:";

	cin>>num2;

	cout<<" Enter third number:";

	cin>>num3;
	if(num1>num2&&num1>num3) {

		cout<<" First number is largest:"<<endl<<"Largest Number= "<<num1;

	} else if(num2>num1&&num2>num3) {

		cout<<" Second number is largest"<<endl<<"Largest number= "<<num2;

	} else {

		cout<<" Third number is    largest"<<endl<<"Largest number= "<<num3;
      
	}
   cout<<endl<< "by: Kian Sagala";	return 0;
}
