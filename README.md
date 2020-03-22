# Miles-per-gallon



#include <iostream>

using namespace std;

int main()

{

    double miles, gallons, MilesPerGallons;
    
    
    // Display the number of gallons 
    cout << "Please enter the number of gallons a car can hold: " << endl; 
    cin >> gallons;  // allow user to enter number of gallons
    
    // display message of number of miles 
    cout << "Please Enter the number of miles: " << endl;
    cin >> miles; /// allow user to enter number of miles 
    
    // calculate the MilesPerGallons
    MilesPerGallons = miles / gallons;
    
    cout << "The number of miles that may be driven per gallon of gas is: " << MilesPerGallons << endl;
    
    
    return 0;
}
