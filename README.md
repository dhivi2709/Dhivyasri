# Dhivyasri
#include<stdio.h>
int main(){
int n;
printf("enter a number:"):
scanf("%d",&n);
while(n!=0){
int a;
a=n%10;
printf("%d\n",a);
n=n/10;
return 0;
}
