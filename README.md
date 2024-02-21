#define _CRT_SECURE_NO_WARNINGS 1
#include <stdio.h>
#define PRISE 1
int main()
{
	int nchi, nmat, neng, nall;
		float nyg;
		printf("请输入语文成绩：\n");
		scanf("%d", &nchi);
		printf("请输入数学成绩：\n");
		scanf("%d", &nmat);
		printf("请输入英语成绩：\n");
		scanf("%d", &neng);
		nall = nchi+ nmat+ neng;
		nyg = (float)nall / 3;
		printf("总分数为%d\n", nall);
		printf("平均数为%f\n", nyg);
		return 0;
}
