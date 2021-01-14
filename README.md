#include<stdio.h>
//1-8复习题编程题2 
void main()
{
    int a[4][4];
    int i,j;
    for(i=0;i<4;i++)
    {
    	for(j=0;j<4;j++)
    	scanf("%d",&a[i][j]); 
	}
	for(i=0;i<4;i++)
    {
		for(j=0;j<4;j++)
   		{
			if(i==j)
    		{
    			a[i][j]=1;
			}
    		if(i!=j)
    		{
    			a[i][j]=0;
			}
		}	
	}
	for(i=0;i<4;i++)
    {
    	for(j=0;j<4;j++)
    	
    	printf("%d ",a[i][j]); 
	}
}

