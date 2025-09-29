# c
#include <iostream>
using namespace std;
int main()
{
	cout << "请输入一个小写字母" << endl;
	char a = getchar();
	
	cout << "大写的前导字符" << endl;
	putchar(a - 1-32);
	putchar('\r');
	putchar('\n');
	cout << "大写的后续字符" << endl;
    putchar(a + 1-32);
	return 0;
}
