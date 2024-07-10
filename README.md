# input-Assignment

// QUESTION NO. 1

#include<iostream>
using namespace std;

int main()
{
  int x;
  cout <<"Enter first number : ";
  cin >> x;
  int y,m;
  cout <<"Enter second number and value for taking modulus:"<<endl;
  cin>>y>>m;

  int z = (x * y) % m;
  cout<<"output is :"<<z;

    return 0;
}

OUTPUT:
Enter first number : 2
Enter second number and value for taking modulus:
3
6
output is :0



