- 👋 Hi, I’m @2697967506
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
2697967506/2697967506 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
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
