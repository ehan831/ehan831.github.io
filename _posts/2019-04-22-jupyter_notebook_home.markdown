---
layout: post
title: "change the home directory for jupyter notebook(mac)"
tags: [jupyter notebook, ipython, home directory, mac]
author: ehan831
comments: true
mathjax: true
---

쥬피터 노트북 홈 디렉토리 변경하기 (아나콘다 홈 디렉토리 변경하기)

<br>

### 1. 주피터 노트북 프로파일 만들기
---

`$ jupyter notebook --generate-config` 을 터미널에서 실행 <br>
- 실행 디렉토리 위치와는 상관이 없음
- 주피터 노트북 폴더에 알아서 만듬
- 자동으로 안되면, PATH 설정 확인하기

아나콘다 기본 경로 기준
`username/.jupyter/jupyter_notebook_config.py` <br>
파일이 만들어진다. 


### 2. jupyter_notebook_config.py 에서 홈 경로 바꾸기
---
![setnum](https://user-images.githubusercontent.com/35619749/82192296-c15f1200-992e-11ea-89aa-ab9301839fff.png)
<br>
<br>

- 214번째 줄에서 주석 # 삭제하고,
- `c.NotebookApp.notebook_dir = ''` 에
- '원하는 경로'에 홈 경로를 입력하기 
<br>
​

저장 후 주피터 노트북을 실행하면 잘 바뀌어 있는 것을 확인할 수 있다.
<br>

### config.py 로 다양한 설정이 가능
---

> [config.py로 패스워드 설정 링크 - plusjune님](https://financedata.github.io/posts/jupyter-notebook-authentication.html)