//# multiplication-by-using-addition
//Finding multiplication  result using addition
#include <stdio.h>
#include <conio.h>
int main(void)
{
    int i,num1,num2,sum=0;
    printf("Enter two number: ");
    scanf("%d%d",&num1,&num2);

    for(i=1;i<=num2;i++)
        sum+=num1;
    printf("\nResult: %d\n",sum);
    return 0;

}
