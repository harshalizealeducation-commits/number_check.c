
#include <stdio.h>

int main()
{
    int n;

    printf("Enter a number: ");
    scanf("%d", &n);

    if (n > 0)
        printf("Positive Number\n");
    else if (n < 0)
        printf("Negative Number\n");
    else
        printf("Zero\n");

    return 0;
}
