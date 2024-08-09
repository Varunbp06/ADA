#include<stdio.h>
#include<stdlib.h>
#include<time.h>
void swap(int *a,int *b)
{
	int temp=*a;
	*a=*b;
	*b=temp;
}
int partition(int arr[],int low,int high)
{
	int pivot=arr[high];
	int i=low-1;
	for(int j=low;j<=high-1;j++)
	{
		if(arr[j]<pivot)
		{
			i++;
			swap(&arr[i],&arr[j]);
		}
	}
	swap(&arr[i+1],&arr[high]);
	return i+1;
}
void quicksort(int arr[],int low,int high)
{
	if(low<high)
	{
		int pi=partition(arr,low,high);
		quicksort(arr,low,pi-1);
		quicksort(arr,pi+1,high);
	}
}
int main()
{
	int n;
	printf("Enter the number of elements:");
	scanf("%d",&n);
	int arr[n];
	srand(time(NULL));
	for(int i=0;i<n;i++)
	{
		arr[i]=rand()%1000;
	}
	clock_t start_time=clock();
	quicksort(arr,0,n-1);
	clock_t end_time=clock();
	double time_taken=((double)(end_time-start_time))/CLOCKS_PER_SEC;
	printf("Time taken to sort %d elements: %lf\n",n,time_taken);
	return 0;
}
