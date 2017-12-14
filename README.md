# Cap.1
 first try for use github
#include"stdio.h"
main()
{
	float x;
	scanf_s("%d", &x);
	if (0 <= x&&x <= 100)
	
		if (x < 90)
			if (x < 80)
				if (x < 70)
					if (x < 60)
						printf("E");
					else
						printf("D");
				else
					printf("C");
			else
				printf("B");
	
	else
		printf("输入非法，重来！");
}
