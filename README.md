//Name: Den Mark S. Maceda
//Date: February 15, 2022
//Course and Section: BSCE 1-1
//PT1 Lab

#include <iostream>

using namespace std;

int main(){
  int number[7], n;

  cout << "Enter range of numbers: ";
  cin >> n;

  cout << "Enter 5 consecutive numbers:\n ";
  cin >> number[0];
  for (n = 1; n <7; n++)


  if ( n % 2 == 0)
    cout << n << " - Even Number.";
  else
    cout << n << " - Odd Number.";

    
  return 0;
}
