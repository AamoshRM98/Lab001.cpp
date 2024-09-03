# Lab001.cpp
// Aamosh Rana Magar
// CSCI 201:Lab Assignment 1


#include <iostream>
#include <cstdlib>
#include <iomanip>
using namespace std;
const double PI: 3.14;
int main()
{
double radius, volume;
cout << "Enter the radius of sphere :";
cin >> radius;
volume = 4.0/3.0 * PI * radius * radius * radius;
cout << "The sphere volume is:"  <<volume <<endl;
return 0;
}
