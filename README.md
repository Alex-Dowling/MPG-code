# MPG-code
C++ code to calculate Miles per Gallon
#include <iostream>
using namespace std;

int main()
{
    //Defining Variables
    int gallons = 15;
    int miles = 375;
    int mpg;

    // Calculating MPG(Miles / Gallons)
    mpg = miles / gallons;

    //Displaying Result
    cout<<"The miles per gallon of the car is "<<mpg<<endl;

    return 0;
}
