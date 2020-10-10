# Activity-A
/*  
    Create a Program to Find Largest Number Among 
    Three Numbers
*/
#include <iostream>
using namespace std;

int main() {
    double n1 , n2 , n3;

    cout << "Input three numbers " <<endl;

    cout <<endl << "Number 1: ";
    cin >> n1;
    cout<< "Number 2: ";
    cin >> n2;
    cout<< "Number 3: ";
    cin >> n3;


    if(n1 >= n2 ){
        if (n1 >= n3)
            cout << n1 <<" is the largest among three number."<< endl;
        else
            cout << n3 <<" is the largest among three number."<< endl;
    } else {
        if (n2 >= n3)
            cout << n2 <<" is the largest among three number."<< endl;
        else
            cout << n3 <<" is the largest among three number."<< endl;
    }
    cout << "Programmed by:Earl Jheed Vallejos"; 
    return 0;
}
