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

//Write a function to count the number of digits in a number and then print the square of this number
#include<iostream>
using namespace std;
int count(int n){
    int count=0;
    while(n>0){
        n=n/10;
        count++;
    }
    return count*count;
}
int main(){
    int n;
    cout<<"Enter n : ";
    cin>>n;
    cout<<count(n);
}

The minimum number of functions present in any C++ program is:
(a)0
(b)1
(c)2
(d)Infinite
ANSWER : (b) 1 

State True and False:
(a) A function may be called more than once from any other function
(b) It is necessary for a function to return some value.
ANSWER : (a) True 
(b) False

Q7: Explore:
Can the same function name be used for different functions without any conflict?
ANSWER : Only if there are number of parameter in 2 functions are different then there is no conflict.
