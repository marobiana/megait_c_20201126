## 문자열 저장 형태
* 문자열은 마지막에는 **\0**이 추가로 들어가서 **문자열**인지 구분된다.  
* 마지막 널 문자(**\0**)를 추가하기 위해 한 칸 더 크게 설정해야 한다.

| [0] | [1] | [2] | [3] | [4] | [5] |
|-----|-----|-----|-----|-----|-----|
| 'H' | 'e' | 'l' | 'l' | 'o' | \0  |

## 문자열 초기화 방법
```
char string[6] = {'H', 'e', 'l', 'l', 'o', '\0'};
char string[6] = "Hello";
char string[] = "Hello";
```

## 문자열의 서식 지정자(출력 format)
* 문자열의 서식 지정자는 **%s**
```
char string[] = "Hello";
printf("%s World", string);
```

> 출력 결과
```
Hello World
```

## 문자열 입력
* String을 입력받을 때는 변수명 앞에 &를 붙이지 않는다.
* scanf_s 함수 두 번째 파라미터에 배열 크기를 넣어야 한다.
```
char inputStr[1024];
printf("단어를 입력하세요:");
scanf_s("%s", inputStr, 1024);
```

# String 관련 유용한 함수들

## string.h
* `#include<string.h>`  

### 문자열(String)의 길이 구하기
|함수명|설명|반환값|
|------|------|------|
|strlen()|문자열의 길이를 반환|null 문자를 제외한 문자열만의 길이|
|strcmp(a, b)|두 문자열 크기 비교(정렬 시 사용)|0: 같은 문자열<br> 음수: b문자열이 크다.<br>양수: a문자열이 크다.|

## stdlib.h
* `#include<stdlib.h>`
* 윈도우 환경에서 visual studio 프로그램에서 include하지 않아도 기본으로 사용 가능

|함수명|설명|반환값|
|------|------|------|
|atoi|문자열 처음에 시작되는 숫자를 int형으로 반환.|int값.<br> 숫자가 없거나 숫자가 문자 중간에 있으면 0|
|atof|문자열 처음에 시작되는 소수를 float형으로 반환|float값|

## 예제
### [예제 1](ex01/ex01.c) : 문자열 초기화, 접근, 값 변경, 입력받기
### [예제 2](ex02/ex02.c) : 문자열 유용한 함수들

## 문제
### [문제 1](quiz01) : 문자열 입력, 접근
### [문제 2](quiz02) : 문자열의 유용한 함수들
### [문제 3](quiz03) : 고급 문제
