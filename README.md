# Task-2-strings
#include <iostream>
#include <string>
using namespace std;

int main() {
    string str1 ="good";
    string str2 = "bye";

string combined = str1 + str2;

cout <<"concatenated string:" << combined << endl;
cout << "length of concatenated string" << combined.length() << endl;

if (str1 == str2) [
    cout << "They are equal values" << endl;
] else [
    cout << "the strings are not equal" << endl; 
]

return 0; 

}
