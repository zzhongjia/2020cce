# 2020cce
## 第一個程式
```c
#include <stdio.h>
int main()
{
    int a, b, c, d;
    scanf("%d",&a);
    printf("%d=50*%d+5*%d+1*%d\n",a,a/50,a%50/5,a%50%5/1);
}  
```
## 第二個程式
```c
#include <stdio.h>
int main()
int a,i,b=0;
scanf("%d",&a);
for(int i=1;i<=a;i++)
{
if(a%i==0)
{
b++;
}
}
printf("%d\n",b);
}
```
## 第三個程式
```c
#include <stdio.h>
int main()
{
   int n,i,ans=0;
   for(i=0;i<10;i++)
   {
   scanf("%d,&n);
   if(n%3==0)
   ans++;
   }
   printf("%d\n"ans);
}
```
## 第四個程式
```c
#include <stdio.h>
int main()
{
   int n;
   scanf("%d", &n);
   if( n>=90 )printf("A\n");
   else if( 90>n&&n>=80 )printf("B\n") ;
   else if( 80>n&&n>=60 )printf("C\n");
   else printf("F\n);
}
```
## 第五個程式
```c
   #include <stdio.h>
   int main()
   {
       int a,b,i,ans=1;
       scanf("%d %d",&a,&b);
       for(i=1;i<=b;i++)
       {
       if(a%i==0 && b%i==0)
       ans=i;
       }
       printf("%d %d\n,a/ans,b/ans);
       }
```  
## 第六個程設
```c
#include <stdio.h>
int a[5]={0,10,20,30,40};
void printfAll(){
for(int i=0;i<5;i++)printf("%d ",a[i]);
   printf("\n");
   }
 int main()
 {

     printfAll();

     int* p=&a[2];
     *p=222;
     printfAll();
     p=p+2;
     *p=666;
     printfAll();
 }
```
## 第七個程式
```c
#include <stdio.h>
int a[5]={0,10,20,30,40};
void printfAll(){
for(int i=0;i<5;i++)printf("%d ",a[i]);
   printf("\n");
   }
 int main()
 {

     printfAll();

     int* p=&a[2];
     *p=222;
     printfAll();

     p=p+2;
     *p=666;
     printfAll();

     p--;
     *p=555;
     printfAll();

 }
 ```
   
