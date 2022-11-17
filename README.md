# cpp1
#c plus plus
#include <iostream>

using namespace std;

int main()
{
    int age;
    cout<<"enter the age:";
    cin>>age;
    if(age<18)
    {
        cout<<"not eligible vote";
    }
    else
    {
        cout<<"eligible vote";
    }

    return 0;
}
