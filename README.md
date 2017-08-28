#include <iostream>
using namespace std;
int main()
{
	double a[12],sum=0,ave;	
	for(int i=0;i<=11;i++){
		cin>>a[i];
		sum=sum+a[i];
	}
	ave=sum/12;
	cout<<"$"<<ave;
	return 0;
}
