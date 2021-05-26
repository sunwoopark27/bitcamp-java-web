*** 2020 . 5 . 26 ***

*** DOM Tree

HTML
<Tag>

DOM Tree 
<OBJECT>
html
    head
         title
             "aaa"
     body
         h1
             "xxx"
         p
             "yyy"

Render Tree
화면에 출력할 객체를 따로 준비



*** HTML 태그 객체와 생성자

var el = document.getElementById("header1");           el.변수
    -> HTMLHeadingElement                                 함수  -> 둘다 자바스크립트에서는 프로퍼티
