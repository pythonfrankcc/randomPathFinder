The use of srand(time(0)) and rand() % 3 -1 ensures that the position is between -1 0 1 in terms of what is added to positional element
The necessary libraries for this are:
#include<cstdlib>
#include<ctime>,
since the algorithm is mainly dependent on rand and srand-> with the seed being time factor

//usage of the said two libraries 
srand(time(0))
rand() % 3 -1 -> core reason for the wavy movement

//best understand the precedence and associativity of operators, my best reference would be the below link
https://www.programiz.com/cpp-programming/operators-precedence-associativity


