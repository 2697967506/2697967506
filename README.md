- š Hi, Iām @2697967506
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
2697967506/2697967506 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include <stdio.h>
#include <stdlib.h>
#define N 10
void main()
{
	int i,a[N],max;
	max=0;
	printf("enter 10 numbers\n");
	for(i=0;i<N;i++)
		scanf("%d",&a[i]);
	for(i=0;i<N;i++)
	{
	if(a[i]>a[max])
		max=i;
	}
	printf("the max is %d",a[max]);
system("pause");
}
