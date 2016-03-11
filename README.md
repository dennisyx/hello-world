#include<stdio.h>

void sort(void)
{
  int a[10]={5,4,8,9,6,5,0,7,2,3};
  int i,j,temp;
  for(i=0;i<9;i++)  //xiao dao da
    for(j=i+1;j<10;j++)
    {
      if(a[i]>a[j])
      {
        temp = a[i];
        a[i] = a[j];
        a[j] = temp;
      }
    }
  for(i=0;i<10;i++)
  {
   printf(%d\n,a[i]);
  }
}

void main()
{
  printf("hello,world\n");
  printf("i am 7ing\n");
  sort();
}


