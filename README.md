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



// QUESTION NO. 2


#include<iostream>
using namespace std;

int main()
{
  int x;
  cout <<"Enter first number : ";
  cin >> x;
  int y;
  cout <<"Enter second number :";
  cin>>y;

  cout<<(x != y )<<" "<<(x >= y);

    return 0;
}


OUTPUT :
Enter first number : 3
Enter second number :2
1 1



// QUESTION NO. 3

#include<iostream>
using namespace std;

int main()
{
  int x,y;
  cin>>x>>y;
  x+=y;
  x-=y;
  x%=y;
  cout<< x;
 

    return 0;
}


OUTPUT:
2
3
2



// QUESTION NO. 4
