# guessingnum
#include <iostream>
#include <cmath>
using namespace std; 



int main(){

int secretnum = 8;
int guess;
int guesscount = 0;
int guesslimit = 3;
bool outofguess = false;

while(secretnum != guess){
    if(guesscount <guesslimit){
        cout <<"enter guess: " <<endl;
         cin >> guess;
         guesscount++;
    }
    else{
        outofguess = true;
        break;
    }
}
if(outofguess){
    cout <<"you lose " << endl;
}
else{

cout <<"you win!" <<endl;
}



    return 0;
}
