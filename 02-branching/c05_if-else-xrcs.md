```c
#define _CRT_SECURE_NO_WARNINGS // allow scanf() in VS C++
#define CUBED 252 // ascii code of 3 superscript

#include <cstdio> // printf(), scanf()
#include <cmath>  // pow()

int main()
{
    // declarations
    double edgeLength, volume;
    char temp;

    // get edge length from stdin
    printf("Stereometrie - Wuerfelvolumen\n\n"
        "Geben Sie die Laenge der Seitenkante ein:\n"
        "a (mm) = ");
    scanf("%lf%c", &edgeLength, &temp);

    // when edge lenth is positive ...
    if (edgeLength >= 0.0)
    {
        // calculate volume and print to screen
        volume = pow(edgeLength, 3);
        printf("\nVolumen V = %lf mm%c\n", volume, CUBED);
    }
    else
    {
        // print error message and leave with code 1
        printf("\nErr. 1: Neg. Kantenlaenge nicht definiert!\n");
        return 1;
    }

    // exit success
    return 0;
}
```