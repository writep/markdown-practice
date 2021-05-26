# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6


# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려강산  
대한사람 대한으로 길이 보전하세

- 띄어쓰기(space바)2번 하거나 br태그를 넣거나
  

# 강조(Emphasis)

_이탤릭_  
**두껍게**  
**_이탤릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>  


# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록(들여쓰기 2회한 후)
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)

<a href="https://google.com">GOOGLE</a>  
[GOOGLE](https://google.com)  
<a href="https://google.com" title="google로 이동">GOOGLE</a>  
[GOOGLE](htpp://google.com "google로 이동")  
*단 target에 관한 속성은 마크다운에서 제공하지 않음  

# 이미지(Images)
![]()
이미지만 불러오기
![HEROPY](https://heropy.blog/css/images/logo.png)  
  
  이미지에 링크를 삽입하기
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog)
  

# 인용문(BlockQuote)
>남의 말이나 글에서 직접 또는 간접으로 따온 문장  
>(네이버 국어사전)
  
>인용문을 작성  
>>중첩
>>>중중첩  
>>>중중첩
  

# 인라인(Inline)코드 강조
CSS에서 `background` 혹은  
`background-image` 속성으로 요소에 배경 이미지를  
삽입할 수 있습니다. (백틱기호 : 숫자 1 왼쪽 기호를 써서 해당 대상을 감싼다)
  

# 블록(Block)코드 강조
```html
<a href="https://google.com">GOOGLE</a>  
```

```css
list .li{
  color:white;
}
```

```javascript
const literAd = document.querySelector('.list');
```

```bash
$ git commit -m 'Study'
```

```plainText
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세
```
  
# 표(Table)

position 속성

값 | 의미 | 기본값
--|:--:|--: 
static | 기준없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 | X
fixed | 뷰포트 | X

콜론(:)기호를 --|--|-- 중 --사이에 넣어주면 정렬을 만들어 줄 수 있음

# 원시 HTML (Raw HTML)
동해물과 <u>백두산</u>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세
  
<a href="https://google.com" target="_blank">GOOGLE</a>   
___
<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY">  

***

# 수평선(Horizontal Rule)

---
***
___