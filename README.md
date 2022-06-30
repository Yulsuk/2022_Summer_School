소속 : 국립안동대학교, 컴퓨터공학과 
=======================
=========사용

이름 : HaBo
-------------
--------------사용

# MD 문법(제목1)

## BlockQuote(제목2)

>This is a first blockqute.
>	>This is a second blockqute.
>	>	>This is a third blockqute.

## 순서가 있는 목록(번호 사용)
1. 첫번째
	- 순서가 없음
	   - 순서가 없음
1. 두번째
	* 순서가 없음
	   * 순서가 없음
1. 세번째
	+ 순서가 없음
	   + 순서가 없음

## 순서가 없는 목록
* 리스트 1
   - 리스트 2
      + 리스트 3

## 들여쓰기
4개의 공백 또는 하나의 탭으로 들여쓰기
들여쓰지 않은 행을 만날 때 까지 변환이 계속됨.

### 정상

	2022/06/21(화) 누리호 발사 성공

		세계에서 7번째 우주 강국

	누리호 성공 축하

한줄씩 띄어쓰지 않으면 줄바꿈 인식이 제대로 안됨

### 비정상

2022/06/21(화) 누리호 발사 성공
	세계에서 7번째 우주 강국
누리호 성공 축하

## 코드
```py
e_tot = 0
o_tot = 0
for x in range(1, 101):
    if x % 2 == 0  :
        e_tot += x
    else :
        o_tot += x

print('1 ~ 100 까지 짝수 합 : {0}, 홀수 합 : {1}'.format(e_tot, o_tot))
```

' ``` ' 으로 묶거나

```
<pre><code>{code}</code></pre>
```
으로 처리함

첫 '```' 뒤에 js, py 등 과같은 사용하는 언어를 선언하면 문법 강조 가능

## Draw Line
각 기호를 3개 이상 사용 '* * *', '***', '*****', '- - -', '--------'
마크다운 문서를 미리 보기로 출력할 때 페이지 나누기 용도로 많이 사용
- - -
* * *

## Link
참조 링크
Link: [google][googlelink]

[googlelink]: https://google.co.kr "Let's go Google"

외부링크
[Google](https://google.co.kr "Let's Go Google")

자동링크
Google Homepage: https://google.co.kr  
Naver Homepage: <https://naver.com>

## 강조
이텔릭체 *별표* 혹은 _언더바_ 를 사용  
두껍게는 **별표** 혹은 __언더바__ 를 사용  
**_이텔릭체_와 두껍게** 를 같이 사용 가능  
취소선은 ~~물결표시~~ 를 사용  

## 영상
![test_pic](pic.png "pic")
![test_pic](https://github.com/Yulsuk/2022_Summer_School/blob/main/pic.png "pic")
![logo] : https://github.com/Yulsuk/2022_Summer_School/blob/main/pic.png "pic"

### 제목3

#### 제목4

##### 제목5

###### 제목6




