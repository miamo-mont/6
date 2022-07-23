# 6
int main()
{
	int a = 0;
	printf("请确认你的性别（1男2女）\n");
	scanf("%d", &a);
	if (a == 1)
	{
		printf("男\n");
	}
	else if (a == 2)
	{
		printf("女");
	}
	else
	{
		printf("输入错误");
	}

	
}
int main()
{
	int ch = 0;
	char password[20] = { 0 };
	int ret = 0;
	printf("请输入密码：>");
	scanf("%s", password);
	while ((ch = getchar()) != '\n')
	{
		;
	}
	printf("请确认密码\n");
	ret = getchar();
		if (ret= 'Y')
			printf("请确成功\n");
		else
			printf("放弃请确\n");
}
