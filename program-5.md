## Write to program to find the value of following expressions:
- `4*5+5/2-9%2`
- `3*5/2+6*9%3+2*3-3`
- `3*(5+2*3)+25/(2*3+2)`

```C
#include <stdio.h>

main(){
    float expr1, expr2, expr3;
    expr1 = 4*5+5/2-9%2;
    expr2 = 3*5/2+6*9%3+2*3-3;
    expr3 = 3*(5+2*3)+25/(2*3+2);
    
    printf("Value of 1st expression is %.2f \n", expr1);
    printf("Value of 2nd expression is %.2f \n", expr2);
    printf("Value of 3rd expression is %.2f \n", expr3);
}
```