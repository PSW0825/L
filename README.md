1. visual studio 2022 실행
2. 코드를 사용하지 않고 계속
3. 도구
4. 명령줄
5. 개발자 명령 프롬포트

mkdir anu //anu 디렉터리 생성

cd anu //anu 디렉터리 들어감

notepad test.c //test.c 메모장을 실행또는 생성

cl test.c 

notepad add.c // add.c 메모장을 실행또는 생성

cl add.c

del *.obj // .obj 파일 모두 삭제

del *.exe /.exe 파일 모두 삭제

cl /c *.c

lib /OUT:my.lib add.obj

link test my.lib //test를 my.lib와 연결

<test.c>
#include <stdio.h>
int main(){
  printf("%d", add(22,33));
}

<add.c>
int add(int a, int b){
  return (a + b);
}

