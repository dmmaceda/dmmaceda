//Name: Den Mark S. Maceda
//Date: February 15, 2022
//Course and Section: BSCE 1-1
//PT1 Lab

#include <iostream>

using namespace std;

int main(){
  int arr[999], n;

  cout << "Enter range of numbers: ";
  cin >> n;

  cout << "Enter 5 consecutive numbers: ";
  for (int i = 0; i < n; i++){
      cin >> arr[i];

  }
 
  for(int i = 0; i < n; i++){
      if(arr[i] % 2 == 0){
          cout << arr[i] << " - Even Numbers\n ";
        
      }
  }
  for(int i = 0; i < n; i++){
      if(arr[i] % 2 == 1){
          cout << arr[i] << " - Odd Numbers\n ";
      }

  }

  
  return 0;
}
