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

#include<iostream>
using namespace std;

int main()
{
  float pi=3.14;
  float radius,height,area,Volume;
  cout<<"Enter base radius of cylinder : ";
  cin>>radius;
  cout<<"Enter height of cylinder : ";
  cin>>height;

  area = pi * radius * radius;  //Area of base
  Volume = area  * height;

  cout<<"The volume of cylinder is :"<<Volume;

    return 0;
}




//QUESTION NO. 5


#include<iostream>
using namespace std;

int main()
{
  char ch1,ch2;
  cout<<"Enter two character : "<<endl;
  cin>>ch1>>ch2;
  cout<<"ch1="<<(int)ch1<<endl<<"ch2="<<(int)ch2<<endl;
    
    int difference = (int)ch1 - (int)ch2;

    cout<<"The difference between ASCII of "<<ch1<<" and "<<ch2<<" is : "<<difference;
    return 0;
}




// QUESTION NO.6


#include<iostream>
using namespace std;

int main()
{
 int i= (4 + 7 / 5 * 6 * 6 + 9) % 100;
 cout<<i;
}

OUTPUT :
49
