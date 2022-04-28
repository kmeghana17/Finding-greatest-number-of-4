#include <stdio.h>

int main()
{
    float a, b, c, d;
    printf("Enter the number a\n");
    scanf("%f", &a);

    printf("Enter the number b\n");
    scanf("%f", &b);

    printf("Enter the number c\n");
    scanf("%f", &c);

    printf("Enter the number d\n");
    scanf("%f", &d);

    if ((a > b) || (a==b))
    {
        if ((a > c) || (a==c))
        {
            if ((a > d) || (a==d))
            {
                printf("a is the greatest number\n");
            }
            else if (d > a)
            {
                printf("d is the greatest number\n");
            }
        }
        else if (c > a)
        {
            if (c > d)
            {
                printf("c is the greatest number\n");
            }
            else if (d > c)
            {
                printf("d is the greatest integer\n");
            }
        }
    }
    else if ((b > a) || (b==a))
    {
        if ((b > c) || (b==c))
        {
            if ((b > d) || (b==d))
            {
                printf("b is the gratest number \n");
            }
            else if (d > b)
            {
                printf("d is the greatest number \n");
            }
        }
        else if (c > b)
        {
            if (c > d)
            {
                printf("c is the greatest number \n");
            }
            else if (d > c)
            {
                printf("d is the greatest number \n");
            }
        }
    }
    
    return 0;
}
