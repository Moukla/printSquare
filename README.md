#include <iostream>
#include <cmath>
using namespace std;
double printSquare(double a);
int main(){
    double a;
    cout<<"Enter the number:";
    cin>>a;
cout<<"The square of the number is: "<<printSquare(a);
return 0;
}
double printSquare(double a){
    int b=2;
    double result = pow(a,b);
    return result;
}
