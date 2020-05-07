markdown
===

* Frequently used mark down code
* 내가 자주 사용하는 마크다운 문법

0.제목
---
```
#  h1
##
...
###### h6

h1에서 h6으로 갈수록 글씨 크기 작아짐.
```

1.헤더(Header)
----
```
헤더 밑에 === 입력
```


2.스몰 헤더(Small Header)
----
```
스몰헤더 밑에 ---입력
```


*3.글씨체, 강조 : Emphasis*
---
~~~
1. bold(굵게 쓰기) : 양쪽에 * or _ 2개 입력
2. italic(기울기)  : 양쪽에 * or _ 1개 입력
3. 밑줄 : <u> ---  </u>
~~~

4.코드삽입
---
```
* 펜스 코드 블럭 지정하고 싶을땐
양쪽에 ``` or ~~~ 지정

* 한줄에 코드 지정하고 싶을 떈
양쪽에 ` 지정 or space bar 4개
```

5.공백삽입, 행 여러줄 띄울 때
---
```
<br /> 입력하면 한 줄 공백생김.
```

6.Readme에 사진첨부하기
---
1. Github Repository에 들어가기
2. Issues 들어간 후 New issue 클릭
3. Leave a comment 부분에 넣을 이미지(사진) 드래그앤 드랍
4. 조금 기다리면 이미지가 깃헙 서버에 업로드가 완료됨. 완료되면 링크가 생성됨.
5. 생성된 링크를 마크다운에 복붙하면 끝!

* 추가
  * `![compare](./image/SPPNet_vs_R-CNN.png)`
  * 주피터 노트북 :  `<img src = "images/overfitting.jpg">`
  * 사이즈 조절할 때 : `<img src = "images/overfitting.jpg" style="width: 700px;"/>`
  * 이미지 정렬 : `<img src = "images/broadcasting.jpg" align="left" style="width: 400px;"/>` <- 왼쪽 정렬
  * 공백(스페이스) 입력 : `&nbsp;`
  * url, 홈페이지 하이퍼링크 연결 : ` [Keras-Initializers](https://keras.io/initializers/).`

7.vscode Markdown PDF : 마크다운으로 작성중인 파일을 PDF 파일로 출력
---
1. 설치 : https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf
2. F1 or 'Ctrl + Shift + P' 선택 후 "markdown-pdf: Export (pdf)" 입력하면  작성중인 폴더 경로에 pdf 파일을 생성함
3. 
``` markdown-pdf: Export (settings.json)
markdown-pdf: Export (pdf)
markdown-pdf: Export (html)
markdown-pdf: Export (png)
markdown-pdf: Export (jpeg)
markdown-pdf: Export (all: pdf, html, png, jpeg)
```

* 참고 및 출처: https://jungmonster.tistory.com/260 [JMob]


8.vscode 단축키 all-in one
---
* 1. 설치 : https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one

* 2. shortcut 단축키
  * `Ctrl + B` : 굵게
  * `Ctrl + I` : 기울기
  * 등등

* 참고 및 출처: https://jungmonster.tistory.com/260 [JMob]

