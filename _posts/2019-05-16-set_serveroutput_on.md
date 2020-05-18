---
layout: post
title: "data grip - set server output on"
tags: [datagrip, db, output]
author: ehan831
comments: true
mathjax: true
---

datagrip 을 사용하고 있는데, 콘솔에서 아무리 SET serveroutput on; 을 해도 결과가 출력되지 않음.

왜지!!!!!!!

![img1](https://user-images.githubusercontent.com/35619749/68359450-37541680-015f-11ea-92aa-abe9176d68fd.png)



1.enable SYS.DBMS_OUT 버튼이 있다. 이것만 눌러주면 됨<br>
![img2](https://user-images.githubusercontent.com/35619749/68359451-37541680-015f-11ea-9544-953e3db1e27b.png)

`단축키로는 Command + F8 이다.`

