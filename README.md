#include<iostream>
using namespace std;
int main()
{
 int a,b,c;
 cout<<"Enter the values of a,b,c";
 cin>>a>>b>>c;
  
 if a>=b && a>=c
{
cout<<"The largest number is:"<<a;
}
if b>=a && b>=c
{
cout<<"The largest number is:"<<b;
}
if  c>=a && c>=b
{
cout<<"The largest number is:"<<c;
}
return 0;
}
