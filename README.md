#include <iostream>
using namespace std;
  int main()
 {
  int score;
  cout<<"Enter your score:";
  cin>>score;
  if(score >= 90)
  {
  cout<< "Your grade is A+";
  }
  else if (score >= 80)
  {
  cout<< "Your grade is A";
  }
  else if (score  >= 70)
  {
  cout<< "your grade is B+";
  }
  else if(score >= 60)
  {
  cout<< "your grade is B";
  }
  else if(score >= 50)
  {
  cout<< "Your grade is C";
  }
  else if(score >= 40)
  {
  cout<< "Your grade is D";
  }
  else if(score <= 39)
  {
   cout<< "Your grade is E \n";
   cout<< "Sorry Better luck next time";
   }
   return 0;
 }
