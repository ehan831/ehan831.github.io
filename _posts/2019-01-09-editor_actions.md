---
layout: post
title: "intellij : editor actions - 라인 편집"
tags: [intellij, actions, 라인편집]
author: ehan831
comments: true
mathjax: true
---

인텔리제이의 기본적인 라인 편집 단축키들 공부

자세한 내용은 [인텔리제이 공식문서](https://www.jetbrains.com/help/rider/Working_in_the_Editor.html)에서 확인

<hr>
<h4>일단 저는 편의상 커서(Cursor)라고 표현을 하고 있지만, 정확한 용어로는 Caret 임.</h4>


1.가장 기본이 되는 복붙 <br>
Command + C 하고 Command + V


​
2.한 줄 복제: 커서 위치와 상관없이 해당 라인이 바로 다음 라인에 복사됨 <br>
Command + D

​
3.한 라인  지우기 <br>
Command + Delete

​
4.Undo, 작업 취소 <br>
Command + Z

​
5.Redo, 취소된 작업 재실행 <br>
Command + Shift + Z


6. Join Lines, 분리된 라인을 이쁘게 붙여줌 <br>
Control + Shift  + J


예시)행
<table>
    <thead>
        <tr>
            <td>실행 전</td>
            <td>실행 후('하나'에 커서를 위치하고 control + shift + j 를 2번)</td>
        </tr>
        <tr>
            <td>
                "하나" + <br>
                "둘" + <br>
                "셋" <br>
            </td>
            <td>"하나둘셋"</td>
        </tr>
    </thead>
</table>


<h4>해당 단축키들은 Preferences > Keymap 에서 확인이 가능하다.

![keymap](https://user-images.githubusercontent.com/35619749/68363748-3a570300-016f-11ea-815c-c3aafc60abfc.png)