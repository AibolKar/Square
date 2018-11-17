# Square
//Program ,which can make a square(very easy,and I am novice).

#include<iostream>
#include<iomanip>    // because we must use setw()
using namespace std;
int main()
{
	int h;   //height
	int l;   //length
	cout<<"H = ";
	cin>>h;  //input height
	cout<<"L = ";
	cin>>l;   //input length
	for(int i=0;i<=l-2;i++)    //cycle
	{
		cout<<"*";   //frame(upper)
	}
	for(int i=0;i<=h;i++)   //cycle
	{
		cout<<"*"<<setw(l-1)<<"*"<<endl;   //frame(Left and right)
	}
	for(int i=0;i<=l-1;i++)      //cycle
	{
		cout<<"*";   //frame(lower)
	}
	return 0;
}
