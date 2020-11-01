---
title:  "MarkDown 문법 정리"
excerpt: "Github 블로그를 시작하며 필요한 Markdown문법을 정리하면 좋을거 같아 포스팅을 진행합니다."

categories:
  - Blog
tags:
  - Blog
  - Markdown
last_modified_at: 2020-11-01
---
Github 블로그를 시작하기 앞서 포스팅에 사용할 Markdown 문법에 대해 

## 표기 방식

기본적인 텍스트 표기 방식입니다. 
마크다운은 줄바꿈을 인식하지 않기 때문에 줄바꿈을 하기 위해서는 라인 끝에 스페이스를 2번 표기해야합니다.

- 강조표시

여러가지 강조 표시가 존재합니다.  
첫번째로 *single asteristks*,  
두번째로 _single underscores_,  
세번째로 **double asterisks**,  
네번째로 __double underscores__,
다섯번째로 ~~cancelline~~가 있습니다.  

---------------------------------------

## 표 만들기  

- 표 내용 중앙 정렬

| 항목 | 가격 | 개수
|:----:|:----:|:----:|
| 라면 | 800원 | 10개 |
| 과자 | 900원 | 20개 |

- 표 내용 좌측 정렬-중앙 정렬-우측정렬

| 항목 | 가격 | 개수 |
|:----|:----:|----:|
| 라면 | 800원 | 10개 |
| 과자 | 900원 | 20개 |

---------------------------------------

## 코드 인용

- PYTHON

```python
s = "Python syntax highlighting"
print(s)
```

---------------------------------------

## 인용
인용문을 사용할때는 > 블럭 인용 문자를 사용하면, 단계별 깊이를 지원한다.

> This is a blockqute

단계별 인용

> This is a first blockqute.
>> This is a seconde blockqute.
>>> This is a third blockqute.

---------------------------------------

## 링크
```
링크 표시법 : [Title](link)
```
[Markdown문법 참고 사이트](https://devinlife.com/howto%20github%20pages/markdown-syntax/)

---------------------------------------
## 이미지 삽입
```
![](https://devinlife.com/assets/images/github캡처.PNG)
```
![](https://devinlife.com/assets/images/github캡처.PNG)