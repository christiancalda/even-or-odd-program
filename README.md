# even-or-odd-program 
codes


#include <iostream>
using namespace std;

int main()
{
    int number,remain;
    cout<< "Plese Enter a Number: ";

    cin >> number,
    
    remain = number % 2;
    if (remain == 0){
    cout <<  number << " is an Even Number";
    }else {
        cout << number << "is a odd Number";
        
    }
    
    
    return 0;
}
