## 문제) struct

### 1. 수업 
* 수업을 관리하는 구조체를 설계하세요.   

>  수업 이름, 강사, 강의실 

* 구조체 변수를 만들어서 아래와 같은 형태로 출력하세요. 

> 출력 예시 

```
수업 이름: c programming 
강사: 신보람 
강의실: 605 
```

### 2. 사각형
* 사각형을 관리하는 구조체를 설계하세요.     
> 가로, 세로  

* 구조체 변수를 만들고, 이를 이용해서 넓이를 구하고 아래와 같이 출력하세요. 

> 출력 예시 

```
가로 : 5 세로 : 4인 사각형의 넓이는 20 입니다.
```

### 3. 성적표
* 3개의 성적을 저장할 수 있는, 성적표를 관리하는 구조체를 설계하세요.   
> 학생 이름, 성적(3개)

* 이름과 3개의 성적을 입력 받고, 평균을 구하여서 아래와 같이 출력하세요. 

> 입력 예시 

```
이름 : 신보람
성적 1 : 96
성적 2 : 85
성적 3 : 70
```

> 출력 예시 

```
신보람 학생 성적표 
96점 85점 70점 
평균 : 83.7점
```

### 4. 회원 관리
* 회원 정보 구조체를 설계하세요. 
> 이름, 나이, 전화번호
* 아래와 같이 배열에 회원정보가 저장되어 있다. 

```
Member members[5] = {
    {.name = "이병헌", .age = 32, .phoneNumber = "010-1111-2222"},
    {.name = "김혜수", .age = 28, .phoneNumber = "010-0000-1111"},
    {.name = "최민식", .age = 30, .phoneNumber = "010-9999-5555"},
    {.name = "손예진", .age = 33, .phoneNumber = "010-8888-7777"},
    {.name = "송강호", .age = 24, .phoneNumber = "010-4444-1111"}
};
```

* 나이를 입력 받고, 입력 받은 나이보다 많은 회원의 정보를 출력하세요.

> 입력 예시 

```
나이: 30
```

> 출력 예시 

```
이름 : 이병헌 나이 : 32 전화번호 : 010-1111-2222
이름 : 손예진 나이 : 33 전화번호 : 010-8888-7777
```


[정답 보기](quiz01.c)
