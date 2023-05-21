
#include <assert.h>
#include <ctype.h>
#include <limits.h>
#include <math.h>
#include <stdbool.h>
#include <stddef.h>
#include <stdint.h>
#include <stdio.h>
#include <stdlib.h>
#include <string.h>

int main()
{
    int n,i;
    scanf("%d",&n);
   long int arr[n],sum=0;
    for (i=0;i<n;i++)
     {scanf("%ld",&arr[i]);
     sum=sum+arr[i];   
    }
        printf("%ld",sum);
    return 0;
}
