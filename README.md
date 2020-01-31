
 #include <stdio.h>

int main()
{
   int n,a[10],i,odd=0,even=0;
   printf("enter the number:");
   scanf("%d",&n);
   for(i=0;i<n;i++)
   {
   scanf("%d",&a[i]);
   }
   for(i=0;i<n;i++)
   {
   if(a[i]%2==0)
   even+=a[i];
   odd+=a[i];
   }
   printf("even=%d",even);
   printf("odd=%d",odd);
  
    return 0 ;
   
}
         output// enter the number:4
         7
         1
         6
         2
         even=8 odd=8
