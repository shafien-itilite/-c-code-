# include <stdio.h>

int main() 
 {  
    int number;
    printf("Enter an integer: ");  
    // reads and stores input
    scanf("%d", &number);

    // displays output
    printf("You entered: %d", number);
   return 0;
}

# include <stdio.h>
# inlcude <stdlib.h>
int main(
{
    double a, b, product;
    printf("Enter two numbers: ");
    scanf("%lf %lf", &a, &b);  
    // Calculating product
    product = a * b;

    // %.2lf displays number up to 2 decimal point
    printf("Product = %.2lf", product);
    
    return 0;
}