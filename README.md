# cason
#include <iostream>
using namespace std;

// find the sum of all multiples below 1000

int main ()
{
  int count = 1000, sum = 0;
  
  while (count > 0)
  {
    if (count%5==0)
        {sum += count; count--;}
    else if (count%3==0)
        {sum += count; count--;}
    else
        count--;
  }
  
  system ("PAUSE");
}
