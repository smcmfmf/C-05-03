# C-05-03

## system 함수로 만든 프로젝트

```c
#include <stdio.h>
#include <stdlib.h>
#include <conio.h>

int main(void)
{
	system("title system(서울 정수 캠퍼스) 함수 사용 프로그램");

	printf("현재 시간 확인");
	system("date");
	printf("시스템 정보");
	system("msinfo32");
	printf("윈도우 빌드 확인\n\n");
	system("winver");
	printf("윈도우 정품인증 확인\n\n");
	system("slmgr /dlv");
	printf("현재 네트워크 구성 정보 출력\n");
	system("ipconfig");
	printf("국내망(1) ping\n");
	system("ping www.boho.or.kr");
	printf("국내망(2) ping\n");
	system("ping www.google.co.kr");
	printf("해외망(일본) ping\n");
	system("ping www.yahoo.co.jp");
	printf("해외망(미국) ping\n");
	system("ping www.amazon.com");
	printf("\n이 프로그램은 10초 후 자동 종료됩니다.");

	Sleep(10000); // 밀리초로 설정  
	system("cls");
	return 0;
}
```
