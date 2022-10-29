# text_Fake_cpp
begging student text
#include"pch.h"
#include<stdio.h>
//int main()
//{
//	int day = 0;
//	scanf("%d", &day);
//	switch (day)
//	{
//	case 1:
//		printf("星期一\n");
//		//break;
//	case 2:
//		printf("星期二\n");
//		//break;
//	case 3:
//		printf("星期三\n");
//		//break;
//	case 4:
//		printf("星期四\n");
//		//break;
//	case 5:
//		printf("星期五\n");
//		//break;
//	case 6:
//		printf("星期六\n");
//		//break;
//	case 7:
//		printf("星期天\n");
//		//break;
//	default:
//		printf("未找到数据");
//		break;
//	}
//	return 0;
//}
//int main()
//{
//	int i = 1;
//
//	while (i<=10)
//	{
//		i++;
//		if (i == 5)
//		{
//			i++;
//			//printf("%d\n",i);
//			//continue;//用于终止本次循环后面的代码
//		}
//		printf("%d\n",i);
//		//i++;
//		//return i;
//	}
//
//}
//int main()
//{
//	int ch = getchar();
//
//	putchar(ch);
//	printf("%c\n", ch);
//	return 0;
//}
//int main()
//{
//	int ch = 0;
//	while ((ch = getchar()) != 'E')
//	{
//		putchar(ch);
//
//	}
//	return 0;
//}
//int main()
//{
//	int k, n = 0;
//	scanf("%d",& k);
//	for (double Sn = 0.0; Sn <= k; n++, Sn += 1.0 / n);
//	printf("%d\n", n);
//		
//	return 0;
//}
//int main()
//{
//	int i = 1;
//	while (i <= 10)
//	{
//		i++;
//		if (i == 5)
//		{
//			i++;
//			//printf("i = %d\n", i);
//			continue;
//		}
//		printf("i = %d\n", i);
//	}
//	return 0;
//}
//int main()
//{
//	int k, n = 0;
//	double Sn = 0;
//	scanf("%d", &k);
//	if (Sn <= k)
//	{
//		n++;
//		Sn += 1.0 / n;
//		printf("%d\n", n);
//	}
//	return 0;
//}
//int main()
//{
//	int k, n = 0;
//	double Sn = 0;
//	scanf("%d", &k);
//	do {
//		n++;
//		Sn += 1.0 / n;
//
//	} while (Sn <= k);
//
//	printf("%d\n", n);
//	return 0;
//
//}
//陶陶摘苹果问题的答案（未写全）
//int main()
//{
//	int counter = 0;
//	int tt,n1=0;
//	// n1, n2, n3, n4, n5;
//	//int n6, n7, n8, n9, n10;
//	int n=0;
//	//scanf_s("%d%d%d%d%d", &n1, &n2, &n3, &n4, &n5);
//	//scanf("%d%d%d%d%d", &n6, &n7, &n8, &n9, &n10);
//	
//	//int arr[20] = { n1,n2,n3,n4,n5 };
//	//scanf("%d\n", &n1);
//	scanf("%d\n", &tt);
//	
//	while(counter<10)
//	{ 
//		//int tt = 100;
//		scanf("%d", &n1);
//		if (tt >n1)
//	{
//		n += 1;
//		counter++;
//	}
//	else
//	{
//		tt += 30;
//		if (tt >= n1)
//		{
//			n += 1;
//			counter++;
//		}
//		else
//		{
//			n += 0;
//			counter++;
//		}
//	}
//	}
//	
//	printf("%d\n", n);
//	return 0;
//}
//int main()
//{
//
//    int m = 0;
//    scanf("%d", m);
//    int t = 1;
//    int n = 0;
//    while (n <= m)
//    {
//        n++;
//        printf("%d\n", n);
//   
//    }
//    return 0;
//}
//void Swap1(int* pa, int* pb)
//{
//	int tep = 0;
//	tep = * pb;
//	*pb = *pa;
//	*pa = tep;
//
//}
//int main()
//{
//	int b = 10;
//	int a = 8;
//	printf("a =%d,b = %d\n", a, b);
//	Swap1(&a, &b);
//	printf("a =%d,b = %d\n", a, b);
//
//	return 0;
//
//}
//#include<math.h>
//int is_prime(int t)
//{
//	for (int n = 2; n <=sqrt(t); n++)
//	{
//		if (t % n == 0)
//			return 0;
//	}
//	return 1;
//}
//int main()
//{
//	int i = 0;
//	for (i = 100; i <= 200; i++)
//	{
//		if (is_prime(i) == 1)
//			printf(" %d", i);
//	}
//
//	return 0;
//}
//int is_year(int n)
//{
//	if ((n % 4 == 0 && n % 100 != 0) || (n % 400 == 0))
//		return 1;
//	else
//		return 0;
//	
//}
//int main()
//{
//	int yr = 0;
//	for (yr = 1000; yr <= 2000; yr++)
//	{
//		if (1 == is_year(yr))
//		{
//			printf("%d ", yr);
//		}
//	}
//	return 0;
//}
//int is_zj(int arr[], int k,int sz)
//{
//	
//	int left = 0;
//	int right = sz - 1;
//	
//	while (left<=right)
//	{
//		int mid = (left + right) / 2;
//		if (arr[mid] < k)
//		{
//			left = mid + 1;
//		}
//		else if (arr[mid] > k)
//		{
//			right = mid - 1;
//		}
//		else
//		{
//			return mid;
//		}
//	}
//	return -1;
//
//}
//int main()
//{
//	int arr[] = { 0,1,2,3,4,5,6,7,8,9 };
//	int k = 7;
//	int sz = sizeof(arr)/sizeof(arr[0]);
//	int ret =is_zj(arr, k,sz);
//	if (ret == -1)
//		printf("未找到相应数字");
//	else
//		printf("已找到，下标为：%d\n", ret);
//		return 0;
//}
//递归函数求阶乘：
int my_double(int n)
{
	if (n >= 2)
		return  n * my_double(n - 1);
}
int main()
{
	int i = 0;
	scanf("%d", &i);
	int ret = my_double(i);
	printf("%d\n", ret);
	return 0;
}
