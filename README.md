// Write a function to print squares of first n natural numbers, taking n as argument to the function
#include <iostream>
using namespace std;
int square(int n){
    int sqr=1;
    for(int i=1;i<=n;i++){
        sqr=i*i;
    }
    cout<<endl;
    return sqr;
}
int main()
{
    int n;
    cout<<"Enter the value of n : ";
    cin>>n;
    for(int i=1;i<=n;i++)
    cout<<square(i);
}

//Write a function that takes the radius of a circle as an argument and returns its area.
#include <iostream>
using namespace std;
float area(int r){
    float ar = 3.14*r*r;
    return ar;
}
int main()
{
    int r;
    cout<<"Enter Radius : ";
    cin>>r;
    cout<<area(r);
}

#include<iostream>
using namespace std;
void printOddNumbers(int a, int b) {
if(a>b){
    printOddNumbers(b, a);
    return;
    }
    for(int i = a; i <= b; ++i) {
        if(i % 2 != 0) {
        cout<<i<<" ";
        }
    }
cout<<endl;
}
int main(){
    int a, b;
    cout<<"Enter a : ";
    cin>>a;
    cout<<"Enter b : ";
    cin>>b;
    printOddNumbers(a,b);
}
