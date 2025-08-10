# return-by-reference-implicit.cpp
//C++ program for return by reference : implicit
//C++ program for return by reference : implicit
#include <iostream>
using namespace std;
int &fun(int &x,int &y){
    if(x>y)
    return x;
    else
    return y;
}
int main() {
    int a=3;
    int b=2;
    fun(a,b)=0;
    cout<<a<<" "<<b;
}
