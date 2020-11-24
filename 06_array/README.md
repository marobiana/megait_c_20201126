## 배열(Array) 설명

하나의 변수 이름에 여러개의 값을 저장 할수 있다.  
  
변수가 하나의 상자에 들어 있는 숫자라면 배열은 아래와 같이 여러 상자를 이어 놓은 형태이다.  
실제로 메모리에도 아래와 같이 연속되게 저장된다.   

- [예제1](ex01/ex01.c): 배열 초기화, 값 수정, 반복문 출력
- [문제1](quiz01/README.md): 문제 8개

### 과제 
- [문제2](quiz02/README.md): 문제 5개

### 추가로 내줄 고급 문제
- [문제3](quiz03/README.md)




--- 학생 보여주기 ---

## 배열 (Array)
```
int scores[10] = {89, 93, 91, 93, 92, 78, 90, 90, 93, 90};
```

* 이와 같은 형태를 **배열**, **Array** 라고 한다.
* 하나의 변수 이름에 여러개의 값을 저장 할수 있다. 
* 변수명 뒤에 [ ] 표시하고 그안에 저장할 값의 개수를 넣는다. 
* 변수가 하나의 상자에 들어 있는 숫자라면 배열은 아래와 같이 여러 상자를 이어 놓은 형태이다. 
* 실제로 메모리에도 아래와 같이 연속되게 저장된다.

	| 89 | 93 | 91 | 93 | 92 | 78 | 90 | 90 | 93 | 90 |
	|----|----|----|----|----|----|----|----|----|----|   

### 아래 코드는 모두 0으로 초기화 된다. 
```
int scores[10] = {0, };
```
  
| 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
|----|----|----|----|----|----|----|----|----|----| 
  
### 아래 코드는 일부 값만 넣고 나머지를 0으로 초기화 된다.

```
int scores[10] = {89, 93, 91, };
```

| 89 | 93 | 91 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
|----|----|----|----|----|----|----|----|----|----|   