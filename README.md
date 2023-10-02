//Reverse of a given number
#include<iostream>
using namespace std;
int main()
{
	int n=0,i,reverse=0,last_digit;
	cout<<"enter the number which you want to reverse:"<<endl;
	cin>>n;
	while(n>0)
	{
		//n=n%10;
		last_digit=n%10;
		reverse=reverse*10+last_digit;
		n=n/10;
	}
	cout<<reverse;
	return 0;
}
