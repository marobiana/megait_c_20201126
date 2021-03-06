## 함수의 기본 구조
```
리턴타입 함수명(매개변수) {
    // 코드 구현...
    return 결과값;
}
```
> 매개변수(Parameter)가 없는 경우  
```
리턴타입 함수명() {
    // 코드 구현...
    return 결과값;
}
```
  
> 리턴값이 없는 경우  
```
void 함수명() {
    // 코드 구현...
}
```
  
> 매개변수(Parameter)가 2개 있는 경우  
```
리턴타입 함수명(자료형 a, 자료형 b) {
    // 코드 구현...
    return 결과값;
}
```
## 함수 선언 방법(1) - 미리 선언 하기
```
리턴타입 함수명(매개변수);   // 메인 함수 위에 선언

int main() {
    // 메인 함수
}

리턴타입 함수명(매개변수) {   // 메인 함수 아래에 구현
    // 코드 구현...
    return 결과값;
}
```
## 함수 선언 방법(2) - 바로 구현하기
```
리턴타입 함수명(매개변수) {   // 메인 함수 위에 선언 없이 바로 구현
    // 코드 구현...
    return 결과값;
}

int main() {
    // 메인 함수
}
```

## 예제
### [예제 1](ex01/ex01.c) : 함수 사용하기
### [예제 2](ex02/ex02.c) : 함수 만들기

## 문제
### [문제 1](quiz01) : 함수 사용하기
### [문제 2](quiz02) : 함수 만들기(기본 연산)
### [문제 3](quiz03) : 함수 만들기(제어문, 반복문)
