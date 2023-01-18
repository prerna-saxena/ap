# ap
ap



#include <iostream>

using namespace std;
float sumofap(float a, float d, int n)
{
    float sum=0;
    for(int i=0; i<n; i++)
    {
        sum=sum+a;
        a=a+d;
        
    }
    return sum;
    
}
