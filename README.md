# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하나님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록  
하나님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이테릭 + 두껍게_**  
~~취소선~~  

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)

<a href='https://google.com'>GOOGLE<a>  
[GOOGLE](https://google.com)  

<a href='https://google.com' title='구글로 이동'>GOOGLE<a>  
[GOOGLE](https://google.com "구글로 이동")  

<a href='https://google.com' title='구글로 이동' target="_blank">GOOGLE<a>

# 이미지(Images)
![헤로피](https://heropy.blog/css/images/logo.png)  

[![헤로피](https://heropy.blog/css/images/logo.png) ](https://heropy.blog/)

# 인용문(BlockQuote)
> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
>(네이버 국어사전)

> 인용문으로 작성
>> 중첩된 인용문
>>> 중중첩된 인용문
>>> 중중첩된 인용문
>>> 중중첩된 인용문
>>>> 중중중첩된 인용문

# 인라인(Inline) 코드 강조

CSS에서 `backround` 혹은 `background-image` 속성으로 요소에 배경
이미지를 삽입할 수 있습니다.
<!-- 백틱임 -->

# 블록(Block) 코드 강조

``` html
<a href='https://google.com' title='구글로 이동'>GOOGLE<a>  
[GOOGLE](https://google.com "구글로 이동")  
```

```css
.list > li {
  pisition:absolute;
  top: 40px;
}
```

```javascript
function func() {
  let a = 1234;
  return a;
}
```

```bash
$ git commit -m 'Study Markdown
```
<!-- $는 터미널에 입력하는 내용이다라는 표시 -->

```plaintext
동해물과 백두산이 마르고 닳도록
하나님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성

값 | 의미| 기본값
--|:--:|--:
 static | 기준 없음 | O
relatuve | 요소 자신| X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X
<!-- 콜론의 위치에 따라 정렬이 달라짐 -->

# 원시 HTML(Raw HTML)

동해물과 <u>백두산</u>이 마르고 닳도록<br/>
하나님이 보우하사 우리나라 만세

<a href='https://google.com' title='구글로 이동' target="_blank">GOOGLE<a>

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY"/>

# 수평선(Horizontal Rule)

---
***
___
