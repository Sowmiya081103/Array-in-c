# Array-in-c
#include <stdio.h>
int main()
{
 

    // array initialization using initialier list

    int arr[5] = { 10, 20, 30, 40, 50 };
 

    // array initialization using initializer list without

    // specifying size

    int arr1[] = { 1, 2, 3, 4, 5 };
 

    // array initialization using for loop

    float arr2[5];

    for (int i = 0; i < 5; i++) {

        arr2[i] = (float)i * 2.1;

    }

    return 0;
}
