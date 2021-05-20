# 210520

## GIT

```bash
$ git reset --hard ORIG_HEAD // 이전 HEAD로 리셋

$ git branch -r // 원격 저장소 브랜치 목록 확인

$ git checkout -t branch_name // 원격 저장소의 브랜치를 받아와서 체크아웃

$ git checkout -b branch_name // 브랜치 생성과 동시에 체크아웃
```

# 제목 (Header)

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

# 문장 (Paragraph)

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
**_에틸릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

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

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>

[NAVER](https://naver.com 'NAVER로 이동!')

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

# 이미지(Images)

![HEROPY](https://github.com/optimizion.png)
[![HEROPY](https://github.com/optimizion.png)](https://github.com/optimizion)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장  
> (네이버 국어 사전)

> 인용문 작성
>
> > 중첩된 인용문
> >
> > > 중중첩된 인용문1  
> > > 중중첩된 인용문2  
> > > 중중첩된 인용문3

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 숭 있습니다.

# 블록(block) 코드 강조

```html
<a href="https://www.google.co.kr/" target="_black">GOOGLE</a>
```

# 표(Table)

position 속성

| 값       |       의미        | 기본값 |
| -------- | :---------------: | -----: |
| static   |     기준 없음     |      O |
| relative |     요소 자신     |      X |
| absolute | 위치 상 부모 요소 |      X |
| fixed    |      뷰포트       |      X |

# 원시 HTML(Raw HTML)

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

<a href="https://naver.com" title="NAVER로 이동" target="_blank">NAVER</a>

---

# 수평선(Horizontal Rule)

---

***

___