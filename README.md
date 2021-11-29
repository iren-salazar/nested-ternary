# nested-ternary
the true statement will be the to be executed

#include <iostream>
using namespace std;
 //nested ternary
int main() {
   int a = 11;
   int b = 5;
   int c = 23;
   
   //condition1                  //exp1             //exp2
   int max = (a>b) ?  ((a>c) ?  11 : 23 ):    ((b>c) ?  5 : 23) ;
   cout << max << endl;
}
 /*output:
 23
 */
