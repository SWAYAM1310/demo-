# demo-
THIS IS MY FIRST JUMP TO GIT REPOSITORY
<br>
THIS IS THE MOST BASIC WAY FOR PRINTING OUT THE PRIME NUMBERS IN A PARTICULAR IN C LANGUAGE.
#include<stdio.h>

int main()

{
    for (int i = 2; i <= 100; i++)
    {
        int k = 0;
        for (int j = 2; j < i; j++)
        {
            if (i%j == 0)
            {
                k = k + 1;
            }
            
        }
        if (k == 0)
        {
            printf("\n%d", i);
        }
        
    }
return 0;    
}
