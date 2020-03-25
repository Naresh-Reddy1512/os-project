#include<stdio.h>
int main()
{
	int i, type[20],n;
	int resp_time[20];
	printf("enter the no,of processes you want: ");
	scanf("%d",&n);
	printf("Enter any data\n");
	scanf("%d",&n);
	for(i=0;i<n;i++)
	{
		printf("Response time of Process is %d  (m_sec) : ",i);
		scanf("%d",&resp_time[i]);
		if(resp_time[i]<1000)
		{
			type[i]=1;
		}
		else
		{
			type[i]=0;
		}
	}
	printf("\nProcess Number\t Response Time\t ProcessType\t Priority");
	for(i=0;i<n;i++)
	{
		printf("\n%d\t\t%dms\t",i,resp_time[i]);
		if(type[i]==1)
		{
			printf("Interactive\tHigh proiority");
		}
		else
		{
			printf("Non-Interactive\tLow priority--");
		}
	}
}
