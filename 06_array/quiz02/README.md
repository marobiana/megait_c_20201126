## 문제) 배열(Array) 응용

### 1. 배열 값 변경
* index와 값을 차례로 입력 받아서, 아래 배열에 해당하는 index에 값을 바꾸고 출력 하세요.  
`int numbers[5] = {3, 5, 2, 10, 39};`

> 입력 예시
 
 ```
 변경할 index와 값을 입력하세요 : 2 16
 ```
 
> 출력 예시

 ```
3 5 16 10 39 
 ```
 
### 2. 점수 채점
* 아래와 같이 O 와 X로 채점 결과가 저장된 배열이 있다.
* 100점 만점 기준으로 몇점을 맞았는지 출력하세요.  
`char scores[10] = {'X', 'O', 'O', 'X', 'X', 'O', 'O', 'O', 'O', 'X'};`

> 출력 예시

 ```
채점 결과는 60점 입니다. 
 ```
 
### 3. 임금 계산
* 아래 배열은 각각 월, 화, 수, 목, 금, 토, 일 7일간의 아르바이트를 한 시간을 나타낸다.
* 시급 기준이 아래와 같을때 7일 동안 일한 총 임금의 값을 출력하세요.

> 평일 시급 : 8500원  
> 주말(토,일) 시급 : 9500원

`int works[7] = {3, 5, 5, 3, 5, 3, 5};`

> 출력 예시

 ```
일주일간 총 임금은 254500원 입니다.
 ```
 
### 4. 배열 값 변경
* 길이가 5인 int 배열을 만든다.
* 수를 계속 입력 받으면서, 입력 받은 수가 짝수 일때만, 배열에 저장한다.
* 배열이 가득차면 입력을 중단하고, 저장된 수들을 출력한다.

> 입력 예시
 
 ```
수를 입력하세요 : 34
수를 입력하세요 : 65
수를 입력하세요 : 23
수를 입력하세요 : 74
수를 입력하세요 : 2
수를 입력하세요 : 74
수를 입력하세요 : 57
수를 입력하세요 : 68
 ```
 
> 출력 예시

 ```
34 74 2 74 68
 ```
 
[정답 보기](quiz02.c)
