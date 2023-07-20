---
title: "시작하는 글 - 테스트"
excerpt: "Git도 배우고 자료 정리하는 차원에서 Github 블로그 서비스로 일단 시작해 본다."

category:
- Blog
tags:
- Blog
last_modified_at: 2023-07-20T14:24
---

### 마크다운 문법 정리  
글머리 # 으로 표현  
# #한개  
## ##두개
### ###세개  
#### ####네개
##### #####다섯개

>인용문은 > 표시 뒤에 쓰면 지금처럼 표현된다.
>> 두개를 하면 인용문 안에서도 단락을 표현할 수 있다.

정렬 목록  
1. 숫자 정렬은 지금처럼 표현할 수 있다.
2. 자동으로 들여쓰기 되며 넘버링 된다.

* 별표로 표시하면 동그라미 정렬기호로 정렬된다.
  * 들여쓰기하면 요렇게
* 다시 내어쓰기 하면 기호를 다시 맞추어 표현되네.

+ 플러스 기호를 써도 동일한 효과를 얻을 수 있다.
  + 들여쓰기~
+ 내어쓰기
  + 다시 들여쓰기 
    + 더 들여쓰니 네모가 되네.

- 마이너스 표시를 해도 동일

코드인용 ` 숫자 1번키 옆 ( 시작 3개 - 끝 3개)
```
function test() {
    console.log("Notice");
}
```

언어 표현하며 코드 인용은 ` 표시 뒤에 언어명 표기
```python
s = "Phython syntax highlighting"
print s
```
수평선
***
별3개
---
하이픈3개

 링크 표시 : [타이틀](링크)  
[구글 검색](https://www.google.com)  
https://www.google.com  

이미지 삽입  
```html
![](https://devinlife.com/assets/images/bio-photo-keyboard-small.jpg)
```
![Keyboard image](https://devinlife.com/assets/images/bio-photo-keyboard-small.jpg)  

table  
| 항목 | 가격 | 개수 |  
|:---:|:---:|:---:|  
| 아메리카노 | 4400원 | 10개 |  
| 카페라떼 | 5000원 | 20개 |   
