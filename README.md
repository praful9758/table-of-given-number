# table-of-given-number
#include<stdio.h>
main()
{
    int i=1,n,p=0;
    printf("kaunsa table pesh karu mere aaka?");
    scanf("%d",&n);
    while(i<=10)
    {
        p=n+p;
        printf("%d\n",p);
        ++i;
    }
}
