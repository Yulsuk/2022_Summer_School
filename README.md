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

크기조절
<img src="pic.png" width="450px" height="300px" title="px(픽셀)크기 설정" alt="testpic"></img><br/>

## 주석
이것은 주석 테스트입니다[^1].

주석은 다수의 줄을 가질 수 있습니다[^2].

단어 또한 쓸 수 있고, 글쓰기 스타일에 따라 맞출 수 있습니다[^note].

[^1]: 첫 레퍼런스
[^2]: 두 번째 레퍼런스
[^note]: 세 번째 레퍼런스

## 표
| 값 | 의미 | 기본값 |
|---|:---:|---:|
| `static` | 유형(기준) 없음 / 배치 불가능 | `static` |
| `relative` | 요소 자신을 기준으로 배치 | |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 | |
| `fixed` | 브라우저 창을 기준으로 배치 | |

## 줄바꿈
일반 텍스트 문장 : 문자 끝에 공백 두번  
테비을 내에서나 일반적인 경우 : <br> 사용

### 제목3

#### 제목4

##### 제목5

###### 제목6




