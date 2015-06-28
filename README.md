#include <iostream>
using namespace std;

// find the sum of all multiples below 1000

int main ()
{
    int count = 0, sum = 0;
    
    while (count < 1000)
    {
        if (count%5==0)
            sum += count;
        else if (count%3==0)
            sum += count;
        
        count++;
    }
    
    cout<<"The sum of all multiples of 3 and 5 below 1000 is "<< sum <<endl;
    
    system ("PAUSE");
    return 0;
}
