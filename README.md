# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
 {
    srand(time(0));  
    int random = rand(); 
    printf("Random number: %d\n", random); 
    return 0;
}
```

# OUTPUT:

![430773340-d4b00109-819a-4e48-a771-eac70beb0a43](https://github.com/user-attachments/assets/b8dfd9e2-fd50-4987-b347-08e8c21ff2ba)

# RESULT:
Thus the program is executed successfully.
