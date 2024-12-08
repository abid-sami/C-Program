//Check Prime number or not
#include<stdio.h>
int main() {
    int i, n, f=1;
    printf("Input Number: ");
    scanf("%d", &n);
    if (n<2)
        printf("Invalid");
    else
    {
        for (i=2; i<=n/2; i++)
        {
            if (n%i==0)
            {
                f=0;
                break;
            }
        }
        if (f==1)

            printf("This is a prime number");
        else
            printf("This is not a prime number");
    }
    return 0;
}
