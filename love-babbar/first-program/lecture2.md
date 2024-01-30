#include<iostream>
int main(){
    std::cout << "hello world";
}

//to get rid of std:: we use "using namespace std"

//Program 2
#include<iostream>
using namespace std;
int main(){
    cout <<"hello world"
    cout << endl; //here endl is used to go to the newline... "\n" can also be used for the same...
}

//Program to take the input from the user
#include<iostream>
using namespace std;
int main(){
    cout <<"enter a number: " <<endl;
    int a;
    cin >> a;
    cout << "you entered " << a << endl;
}

// DATATYPES IN C++
    BUILT-IN / PRIMITIVE :- 
        Integer:-
            int
            char
        floating :-
            float
            double
        void
    
    DERIVED :-

    USER DEFINED :-