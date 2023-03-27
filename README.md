# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
~~**_이텔릭 + 두껍게 + 취소선_**~~  
<u>밑줄</u>
<u>~~**_이텔릭 + 두껍게 + 취소선 + 밑줄_**~~</u>

# 목록(List)

1. 순서가 필요한 목록  
1. 순서가 필요한 목록  
    1. 순서가 필요한 목록  
    1. 순서가 필요한 목록  
1. 순서가 필요한 목록  


- 순서가 필요하지 않는 목록
- 순서가 필요하지 않는 목록
- 순서가 필요하지 않는 목록
    - 순서가 필요하지 않는 목록
    - 순서가 필요하지 않는 목록   

- 순서가 필요하지 않는 목록


# 링크(Links)  
<!-- []() -->
 <a href = "https://www.google.com">Google </a>

 [GOOGLE](https://www.google.com)

 <a href = "https://www.naver.com" title ="NAVER로 이동1">NAVER </a>

 [NAVER](https://www.naver.com "NAVER로 이동!")

 <a href = "https://www.naver.com" title ="NAVER로 이동1"
            traget="_blank">NAVER </a>

# 이미지(Image)

<!-- ![]() -->

![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)

# 인용문(BlockQuote)

> 남이 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문 1
>>> 중중첩된 인용문 2
>>> 중중첩된 인용문 3

# 인라인(inline) 코드 강조

css에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있다.

# 블록(block) 코드 강조

<a href = "http://www.google.co.kr" target = "_blank">GOOGLE</a>

```html
<a href = "http://www.google.co.kr" target = "_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA'
  return = a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```


# 표(Table)

position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | x
absolute | 위치 상 부모 요소 | x
fixed | 뷰포트 | x

# 원시 HTML (Raw HTML)

동해물과 <span style = "text-decoration: underline;">백두산</span>이 마르고 닭도록<br />
하느님이 보우하사 우리나라 만세

<a href="https://www.naver.com" 
        title = "NAVER로 이동!"target = "_blank">NAVER</a>

---

<img width = "70" src = "https://heropy.blog/css/images/logo.png" alt = "HEROPY">

---

# 수평선 (Horizontal Rule)

---

***

___