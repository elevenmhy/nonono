# nonono
learn
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>
int main()
{
	int a = 10;
	scanf("%d", &a);
	printf("%d/n", a);
	return 0;
}
{
	char arr[5] = { 0 };
	scanf("%s", arr);
	printf("%s/n", arr);
	return 0;
}
int main()
{
	int num1 = 0;
	int num2 = 0;
	int sum = 0;
	scanf("%d%d", &num1, &num2);
	sum = num1 + num2;
	printf("sum = %d\n",sum);
	return 0;
}
enum Sex
{
	MALE,
	FEMALE,
	SECRET
};
int main()
{
	printf("%d\n", MALE);
	printf("%d\n", FEMALE);
	printf("%d\n", SECRET);
	return 0;
}
