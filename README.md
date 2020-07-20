# fuctions

#include<iostream>
using namespace std;
int main()
{
	
	int i,n,count=0;
	cout<< "enter the number :";
	cin>> n;
	if(n ==0)
	{
		cout<< "\n"<< n << " is not prime";
		exit(1);
	}
	else
	{
	
	
	
	for(i=2;i<n;i++)
	
		if(n%i==0)
		
			count++;
		}
		
		if(count>1)
		
		
		cout<< "\n"<< n << " is not prime ";
		
			else
			
			cout<< "\n" << n << " is a prime ";
		
	

	return 0;
}
