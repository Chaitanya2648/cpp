# cpp
this is cpp program that is c++ program to compile run time polymorphism
#include<iostream>
using namespace std;
class A
{
        int a;
    public:
        void display()
        {
            cout<<"class a";
        }
};
class B : public A
{
    int b;
public:
    void display()
    {
        cout<<"class B:";
    }
};
int main()
{
    B f;
    f.display();
}
