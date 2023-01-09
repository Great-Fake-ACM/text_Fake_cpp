# text_Fake_cpp
begging student text
//struct Stu
//{
//	char name[20];
//	short age;
//	char tele[12];
//	char sex[5];
//}s1,s2,s3;//全局变量

//struct Stu
//{
//	char name[20];
//	short age;
//	char tele[12];
//	char sex[5];
//};//全局变量
//int main()
//{
//	Stu s1 = {"张三",20,"15249287634","男"};//局部变量
//	struct Stu s2 = { "旺财",12,"12554444889","保密" };
//	return 0;
//}
//struct S
//{
//	int a;
//	char c;
//	char arr[20];
//	double d;
//};
//
//struct T
//{
//	char ch[10];
//	struct S s;
//	char* pc;
//};
//
//int main() 
//{
//	char arr[] = "hello world\n";
//	struct T t = { "hehe",{100,'w',"hello world",3.14},arr };
//	printf("%s\n", t.ch);
//	printf("%s\n", t.s.arr);
//	printf("%lf\n", t.s.d);
//	printf("%s\n", t.pc);
//	return 0;
//}
//typedef struct Stu
//{
//	char name[20];
//	short age;
//	char tele[12];
//	char sex[5];
//}Stu;//全局变量
//void Print1(Stu tmp)
//{
//	printf("name: %s\n", tmp.name);
//	printf("age: %d\n", tmp.age);
//	printf("tele: %s\n", tmp.tele);
//	printf("sex: %s\n", tmp.sex);
//}
//void Print2(Stu* tmp)
//{
//	printf("name: %s\n", tmp->name);
//	printf("age: %d\n", tmp->age);
//	printf("tele: %s\n", tmp->tele);
//	printf("sex: %s\n", tmp->sex);
//}
//int main()
//{
//	Stu s = { "李四",40,"10885644365","男"};
//	Print1(s);
//	Print2(&s);//打印首选Print2可以减少空间的占用
// //函数传参石，参数需要压栈，如果传递一个结构体对象的时候，结构体过大
// ，参数压栈的系统开销打，会导致性能下降
//	//结构体传参要传地址
//	return 0;
//}

int Add(int a, int b)
{
	return a + b;
}
int main()
{
	int a = 10;
	int b = 20;
	int ret = 0;
	ret = Add(a, b);
	return 0;
}
//栈区包含了局部变量，函数的形式参数，函数调用也开辟空间
//堆区包含了动态内存分配，malloc/free,realloc,ralloc
//静态区包含了全局变量，静态变量
//数据结构
//----线性数据结构
//顺序表
//链表
//栈
//队列
//---树形数据结果
//二叉树
