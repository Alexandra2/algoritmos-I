#include "stdafx.h"
#include "conio.h"
#include<iostream>
#include"math.h"

using namespace std;

float serie (float x,int n);
int fac (int a);

void main()
{ float x,sumatoria;
  int n; 
 cout<<"Ingrese valor de n:";
 cin>>n;
 cout<<"Ingrese el valor de x:";
 cin>>x;

 sumatoria= serie(x,n);
 cout<<"La sumatoria es:"<<sumatoria;
 
 _getch();

}

float serie (float x, int n)

{ int sig,i;
 float s;

 sig=1;
 s=0;

 for(int i=1;i<=n;i++)
	 { s= s+sig *pow(x,i)/fac(i);
       sig= sig *(-1);
     }

    return s;
}

 int fac(int n)
 { int b=1;
  for(int i=1; i<=n; i++)
	  b=b*i;
    return b;
 }
  

 
