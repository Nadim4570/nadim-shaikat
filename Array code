//EX.1 monthly expenses


#include<stdio.h>
void main()
{
    float expenses[13];
    int n;
    for(n=0;n<12;n++)
    {
        printf("Enter expenses for month %d: ",n+1);
        scanf("%f",&expenses[n]);
    }
    for(n=0;n<12;n++)
    {
        printf("Month %d = $%.2f\n",n+1,expenses[n]);
    }
}

//EX.2 grading and average

#include<stdio.h>
void main()
{
    int mark[10],sum=0,i,avg;
    for(i=0; i<10; i++)
    {
        printf("Enter the person %d's mark: ",i+1);
        scanf("%d",&mark[i]);
        if (mark[i]>100)
        {
            printf("the hight mark possible is 100\nEnter correct grade:");
            scanf("%d",&mark[i]);
        }
        sum=sum+mark[i];
    }
    avg=sum/10;
    printf("Average is %d",avg);
}

//EX.3 multiplying numbers in the even array

#include<stdio.h>
int main()
{
    int a[9],i;
    for(i=0; i<9; i++)
        a[i]=i;
    for(i=0; i<9; i++)
    if(i%2==0)
    a[i]=a[i]*3;
    for(i=0; i<9; i++)
        printf("%d ",a[i]);
    return 0;
}

//EX.4 fibonacci sequence

#include<stdio.h>
void main()
{
    int a[100],n,i;
    a[0]=0;
    a[1]=1;
    printf("%d\n",a[0]);
    printf("%d\n",a[1]);
    for (i=2; i<15; i++)
    {
        a[i]=a[i-1]+a[i-2];
        printf("%d\n",a[i]);
    }
}

//EX.5 minimum number

#include <stdio.h>

void main()
{
    int n,start=0,i,extra,smallest=0;
    printf("Enter the size of the array:");
    scanf("%d",&n);
    int a[n];
    
    for(i=0;i<n;i++)
    {
        printf("Enter the value of array[%d]:",i);
        scanf("%d",&a[i]);
    }
    for(i=0;i<n;i++)
    {
        if(a[i]<a[smallest])
        smallest=i;
    }
    extra=a[0];
    a[0]=a[smallest];
    a[smallest]=extra;
    
    printf("%d",a[0]);

}

//EX.6 minimum number sorting

#include <stdio.h>

void main()
{
    int n,start=0,smallest=0,extra,i;

    printf("Enter the size of the array:");
    scanf("%d",&n);
    int a[n];

    for(i=0;i<n;i++)
    {
        printf("Enter the value of array[%d]:",i);
        scanf("%d",&a[i]);
    }
    for(start=0;start<n;start++)
    {
        for(i=start;i<n;i++)
        {
            if(a[i]<a[start])
            {
                smallest=i;
                extra=a[start];
            a[start]=a[smallest];
            a[smallest]=extra;

            }
        }
        printf("%d ",a[start]);
    }
}


//EX.7 find maximum value and print index

#include<stdio.h>
  void main(){
  int index=1,maximum=-32145,i;
  int A[7]={1,2,6,-1,-2,-3};

  for(i=0;i<7;i++)
  {
      if (maximum<A[i])
      {
        maximum=A[i];
        index=i;
      }
  }
  printf("Maximum value : %d\n",maximum);
  printf("Index : %d",index);

  }
  
  //EX.8 merge 2 arrays into one
  
  #include<stdio.h>
  void main()
  {
    int A[7]={1,2,3,4,6,8,-9};
    int B[7]={2,5,6,9,-7,4,11};
    int C[14];
    int i,j=0;
    for(i=0;i<7;i++,j++)
    {
      C[j]=A[i];
    }
    for(i=0;i<7;i++,j++)
    {
      C[j]=B[i];
    }
    for(i=0;i<14;i++)
    {
      printf("C[%d] = %d\n",i,C[i]);
    }

  }
  
  //EX.9 searching in array
  
    void main(){
     int item,index=0,i;
     int A[]={0,1,2,3,5,6};
     scanf("%d",&item);

     for(i=0;i<6;i++)
     {
        if(item==A[i])
        {
           index=i;
           break;
        }
     }

     if(i==6)
     printf("Not Found");
     else
     printf("Found in index %d",index);
    }
    
    //EX.10  user defined functions in array
    
    #include<stdio.h>
#define SIZE 5
void printArray(int a[],int size)
{
   int i;
    for(i=0;i<size;i++)
      printf("%d",a[i]);
}
int modifyElement(int item){
   return item+5;
}
 void main()
 {
   int A[SIZE],i;

    for(i=0;i<SIZE;i++)
     scanf("%d",&A[i]);
     A[3]=modifyElement(A[3]);
     printArray(A,SIZE);

}
