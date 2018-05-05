# Daily-Challenge
dc's of skillrack
#include<stdio.h>
#include <stdlib.h>

int main()
{
    int n;
    scanf("%d",&n);
    int a[n],b[n],k=0;
    for(int i=0;i<n;i++)
        scanf("%d",&a[i]);
    for(int i=0;i<n;i++) 
    {
        int c=a[i];
        int r=(c/10)%10;
        if(r%2!=0)
            b[k++]=a[i];
    }
    int sum=0;
    for(int i=0;i<k;i++) 
        sum=sum+b[i];
        
    if(sum)
        printf("%.2f",sum/(float)k);    
    else
        printf("0.00");

}


#include<stdio.h>
#include <stdlib.h>

int main()
{
    int n;
    scanf("%d",&n);
    int a[n],b[n],k=0;
    for(int i=0;i<n;i++)
        scanf("%d",&a[i]);
    for(int i=0;i<n;i++) 
    {
        int c=a[i];
        int r=(c/10)%10;
        if(r%2!=0)
            b[k++]=a[i];
    }
    int sum=0;
    for(int i=0;i<k;i++) 
        sum=sum+b[i];
        
    if(sum)
        printf("%.2f",sum/(float)k);    
    else
        printf("0.00");

}


5
10 2334 65 76 80
806.67
