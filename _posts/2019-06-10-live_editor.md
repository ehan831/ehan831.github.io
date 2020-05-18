---
layout: post
title: "intellij - Live Edit"
tags: [intellij, LiveEdit, 인텔리제이, 라이브에디트, js html css]
author: ehan831
comments: true
mathjax: true
---
intellij html, css, javascript 로 이것저것 공부해보고 있는데, 웹 브라우저에 반영이 너무나도 늦을 때 ... 새로 고침을 아무리 눌러도 추가한 코드가 업데이트 되지 않을 때 ...

intellij 에서 제공하는 live edit 를 쓰면 해결됨.<br>
`주의 - intellij ultimate 버전에서만 제공되는 기능이다.`

[영문 가이드 링크](https://www.jetbrains.com/help/idea/live-editing.html#Live_Editing.xml)


<hr>
<h3>문제 상황</h3>
intellij 에 3번 함수를 추가했는데, 브라우저에선 안 보이는 상황

![img1](https://user-images.githubusercontent.com/35619749/68358490-03c3bd00-015c-11ea-90c0-e1bcb5d51713.png)
<br>
왜 3번은 없냐 ...

<hr>
<h3>해결 방법</h3><br>

### 1.인텔리제이에서 preferences > plugins 에서 LiveEdit 를 검색하고 설치하기<br>
![le2](https://user-images.githubusercontent.com/35619749/68358500-07efda80-015c-11ea-9078-63efd0755d06.png)

설치하면 인텔리제이를 재시작해야 한다.


### 2.크롬 > 설정 > 확장 프로그램 열기<br>
![le3](https://user-images.githubusercontent.com/35619749/68358501-08887100-015c-11ea-85c2-8a5a1b10be3d.png)


### 3.크롬 웹 스토어 열기<br>
![le4](https://user-images.githubusercontent.com/35619749/68358502-08887100-015c-11ea-89f4-466016ceb53a.png)


### 4.JetBrains IDE Support 를 크롬에 추가하기<br>
![le5](https://user-images.githubusercontent.com/35619749/68358503-08887100-015c-11ea-941f-9b254edc2ec9.png)

끝. 

인텔리제이에 Plugin 설치하기( Live Edit )
크롬에 확장 프로그램 설치하기 ( JetBrains IDE Support )

두 개만 하면 바로바로 새로고침 누르자마자 브라우저에 변경 내용이 반영되는 것을 볼 수 있음.
문제 해결!!

`크롬 브라우저가 아래와 같이 보이면 됩니다 !!`
![le6](https://user-images.githubusercontent.com/35619749/68358504-08887100-015c-11ea-89ca-f88737413460.png)
