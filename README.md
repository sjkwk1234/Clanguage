#include <stdio.h> //printf()를 사용하려면 필요하다

int main(void) {  //main()함수를 정의한다
  printf("%d은 정수이다\n",1); //1이 앞에 추가된다
  printf("%.2f는 실수이다\n",1.12); //1.12가 앞에 추가된다
  printf("%c는 문자이다\n", 'C'); //C가 앞에 추가된다
  printf("%s는 문자들의나열이다\n","Good Games"); // Good Games가 앞에 추가된다

  return 0; // 함수를 종료한다
}
