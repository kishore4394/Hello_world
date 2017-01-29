# Hello_world
It is my first repository

Hi i am going to write a C Program for sorting of elements

#include<stdio.h>
#include<conio.h>
void main()
{
int a[10],i,j,n,temp=0;
clrscr();
printf("\n Hello world i am going to sort the elements in the array in ascending order");
printf("\n Enter the number of the elements in the array:");
scanf("\t%d",&n);
printf("\n Enter the elements in the array:");
for(i=0;i<n;i++)
scanf("\n%d",&a[i]);
Printf("\n Before Sorting the array is:");
for(i=0;i<n;i++)
printf("\n %d",a[i]);
printf("\n After sorting the array is:");
for(i=0;i<n;i++)
{
for(j=i+1;j<n;j++)
{
if(a[i]>a[j])
{
temp=a[i];
a[i]=a[j];
a[j]=temp;
}
}
}
for(i=0;i<n;i++)
printf("\n %d",a[i]);
}

