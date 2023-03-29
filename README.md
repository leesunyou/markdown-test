# 제목 (Header)

# 제목 1 (h1)
## 제목 2 (h2)
### 제목 3 (h3)
#### 제목 4 (h4)
##### 제목 5 (h5)
###### 제목 6 (h6)


# 문장 (Paragraph)

Don't ever say it's over, if I'm breathin'
Racing to the moonlight, and I'm speedin'


# 줄바꿈 (Line Breaks)

(띄어쓰기 2번 or br태그 사용) <br>
Don't ever say it's over, if I'm breathin'  
Racing to the moonlight, and I'm speedin'  
I'm headed to the stars, ready to go far  
I'm STAR WALKIN'


# 강조 (Emphasis)

_이텔릭_ (_으로 글을 감싸기)  
**두껍게** (* 2개로 글을 감싸기)  
**_이텔릭 + 두껍게_** (* 2개, _으로 글을 감싸기)  
~~취소선~~ (~ 2개로 글을 감싸기)  


# 목록 (List)

ul 태그
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록  
    (목록 안에 목록 넣는 방법 = 띄어쓰기 2번 or tab 2 번)
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

ol 태그
- 순서가 필요없는 목록
- 순서가 필요없는 목록
- 순서가 필요없는 목록
    - 순서가 필요없는 목록
    - 순서가 필요없는 목록 
- 순서가 필요없는 목록


# 링크 (Links)

<a href="https://google.com">Google</a>

[Google](https://google.com)  
: [] 안에 이름, () 안에 링크 주소

<a href="https://naver.com" title="Naver로 이동 -ㅅ-" target="_blank">Naver</a>

# 이미지 (Images)

![Rooibos](http://sunyou0620.dothome.co.kr/img/s1_rooibosgoji_01.jpg)


# 인용물 (BlockQuote)

> RGE전 패배는 괜찮다.
"중요한 것은 꺾이지 않는 마음"  
> ( DRX Deft )

> 인용문을 작성하세요 -ㅅ-
>> 중첩된 인용문
>>> 중중첩된 인용문1
>>> 중중첩된 인용문2


# 인라인 (inline) 코드 강조
백틱 기호(option + ₩) 사용  
<br>
CSS에서  `background` 혹은  
`background-image` 속성으로  
요소에 배경 이미지를 삽입할 수 있습니다.


# 블록 (block) 코드 강조

```html
<a href="https://google.com">Google</a>
```

```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
I'm headed to the stars,  
ready to go far
I'm STAR WALKIN'
```


# 표 (Table)

position 속성

이름 | 포지션 | 월즈 우승 횟수
--|--|--
BeryL | SPT | 2
Cuzz | JGL | 0
Faker | MID | 3
Deft | BOT | 1
Kiin | TOP | 0

이름 | 포지션 | 월즈 우승 횟수
:--:|:--:|:--:
BeryL | SPT | 2
Cuzz | JGL | 0
Faker | MID | 3
Deft | BOT | 1
Kiin | TOP | O

이름 | 포지션 | 월즈 우승 횟수
--:|--:|--:
BeryL | SPT | 2
Cuzz | JGL | 0
Faker | MID | 3
Deft | BOT | 1
Kiin | TOP | 0


# 원시 HTML (Raw HTML)

Don't ever say it's over, if I'm breathin'<br>
Racing to the moonlight, and I'm speedin'<br>
I'm headed to the stars, ready to go far<br>
I'm <span style="text-decoration: underline;">STAR WALKIN'</span>


# 수평선 (Horizontal Rule)

---

***

___