#include <iostream>
#include <string>
#include <algorithm>
using namespace std;

char Caeser(char&, int&);

int main(){
  string code;
  char variety;
  cout<<"please enter a code "<< endl;
  cin >> code;
  cout<<"please enter your alphabet" << endl;
  cin >> variety;
  
  int dx;
  dx = (int) (variety - 'a');
  for(auto i:code){
    cout << Caeser(i, dx);
  }
  cout << endl; 
}

char Caeser(char& c, int& dx){
   int n = c - 'a';
   n = (n + dx) % 26;
   char co = static_cast< char >(n + 'a');
   return co;

}
