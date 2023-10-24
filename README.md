// Write a program to find the product of two numbers using pointers.
#include<iostream>
using namespace std;
int main(){
    int a;
    cout<<"Enter a : ";
    cin>>a;
    int b;
    cout<<"Enter b : ";
    cin>>b;
    int* p1=&a;
    int* p2=&b;
    cout<<(*p1)*(*p2);
}

Q2 : int *p, q;
(a) p is a pointer and q is an integer.
(b) p and q both are pointers.
(c) P and q both are integers.
(d) Syntax is incorrect.
ANSWER : (a) p is a pointer and q is an integer.

// Find the output of the following code snippet.
#include<iostream>
using namespace std;
int main(){
int a=10,b=20;
int *ptr=&a;
b =*ptr+1;
ptr=&b;
cout<<*ptr<<" "<<a<<" "<< b;
}

// Q4: Find the output of the following code snippet.
int a = 15, b = 20;
int *ptr = &a;
int *ptr2 = &b;
*ptr = *ptr2;
cout<<*ptr<<endl<<*ptr2;
(a) ptr now points to b
(b) ptr2 now points to a
(c) a gets value of b
(d) b gets value of a
ANSWER : (c) a gets value of b

Is the following program snippet correct?
int a = 10, b = 20;
int *ptr;
*ptr = 5;
ANSWER : No, this code contain error in 3rd line.
