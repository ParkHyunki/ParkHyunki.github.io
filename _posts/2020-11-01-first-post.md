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

기본적인 텍스트 표기 방식이다. 마크다운은 줄바꿈을 인식하지 않는다.

줄바꿈을 하기 위해서는 라인 끝에 스페이스를 2번  
표기해야한다.

여러가지 강조 표시가 존재한다.  
첫번째로 *single asteristks*,  
두번째로 _single underscores_,  
세번째로 **double asterisks**,  
네번째로 __double underscores__,
다섯번째로 ~~cancelline~~가 있다.  

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